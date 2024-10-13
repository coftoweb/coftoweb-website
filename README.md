# coftoWeb

hard rest on old commit
```bash
git reset --hard <commit-hash>
```

```bash
git push --force origin <branch-name>
```


how to bundle html css js

step1: create src folder move all your html,css,js there
step2: npm install -D html-bundle
step3: replace package.js content with
```json
{
  "scripts": {
    "build": "html-bundle"
  },
  "devDependencies": {
    "html-bundle": "^6.1.7"
  },
  "dependencies": {
    "jquery": "^3.7.1",
    "popper.js": "^1.16.1"
  }
}
```
step4: npm run build


Added Cloudflare.