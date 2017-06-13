# Miscellanous snippits

_Make an empty commit to force a redeploy_

```
git commit --allow-empty -m 'redeploy' && git push
```

_Test that an environment works before you merge it_

```
CODE=$(curl -s -w '%{http_code}' $(platform url -e dev --pipe | head -n 1) -o /dev/null)
[ "$CODE" = 200 ] && platform merge -e dev
```

_Write Platform environment variables to a file_
```
php -r "echo json_decode(base64_decode(getenv('PLATFORM_VARIABLES')), true)['FILE_VALUE'];" > file_name.txt
```
or
```
python -c 'import json,base64,os;print json.loads(base64.b64decode(os.getenv("PLATFORM_VARIABLES")))["FILE_VALUE"];' > file_name.txt
```
