1. Add & commit .gitignore
1.1. Check package.json and update project name.
2. > npm install (this will add node_modules and dist files)
3. > npm run build.

if following error is received; delete package-lock.json and reinstall with > npm install.
```
npm ERR! enoent ENOENT: no such file or directory, open '/Users/cesar/epicodus/package.json'
```

* also, make sure that webpack.config.js title matches your current project name.


* Create an environment from scratch cheatsheet: https://striped-yogurt-283.notion.site/JavaScript-Dev-Environment-Notes-32267eab60d54d12b03f88eb7e77d84e