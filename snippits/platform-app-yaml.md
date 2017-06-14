# .Platform.app.yaml Snippits

_Run a cron command only on a given branch_

```
if [ "$PLATFORM_BRANCH" = master ]; then
  bin/console whatever
fi
```

or

```
cmd: '[ "$PLATFORM_BRANCH" = "master" ] && bin/console whatever'
```

_Run Composer from the build hook_

```
hooks:
    build: |
        composer install --no-dev --prefer-dist --no-progress --no-interaction --optimize-autoloader
```

_Exit without completing the build if a build or deploy command fails_

```
hooks:
    build: |
        set -e
```

_Set an environment variable only if it does not already exist_

```
hooks:
    build: |
        if [ -z "$MY_ENV" ]; then
            export MY_ENV=foo
        fi
```
