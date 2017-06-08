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

