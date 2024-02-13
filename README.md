# choi's tech blog
![image](https://github.com/choi3179/choi3179.github.io/assets/66417882/3496f2ae-acd4-4bbb-8631-8fdbb7295f1c)

### How To Contribute
- WSL Ubuntu 22.04 LTS
- vim
- html/css

### How To Deploy
#### STG dev  ( choi3179-b773.web.app )
#### STG prod ( choi3179.github.io )

|STG|BRANCH|TRIGGER|URL|
|------|---|---|---|
|DEV|Branch of PR|manual firebase cmd|[choi3179-b773.web.app](https://choi3179-b773.web.app)|
|PROD|main|Auto Github Action|[choi3179.github.io](https://choi3179.github.io)|
```bash
# manual firebase cmd*
$ firebase deploy
=== Deploying to 'html5-standard'...

i  deploying hosting
i  hosting[choi3179-b773]: beginning deploy...
i  hosting[choi3179-b773]: found 359 files in /
✔  hosting[choi3179-b773]: file upload complete
i  hosting[choi3179-b773]: finalizing version...
✔  hosting[choi3179-b773]: version finalized
i  hosting[choi3179-b773]: releasing new version...
✔  hosting[choi3179-b773]: release complete

✔  Deploy complete!

Project Console: https://console.firebase.google.com/project/html5-standard/overview
Hosting URL: https://choi3179-b773.web.app
```

### Docker Pull Command
``` bash
$ docker pull choi3179/blog
```

### Design Template
- https://html5up.net/paradigm-shift

