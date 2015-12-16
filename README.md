### psnpmplaybk
####2
- 11
Remove a package:
```
npm uninstall package --save
```
- 12 
install specific version package
```
npm install pname@">1.1.0 <1.4.0" 
```
Typically install latest version of 1.3.x

save exact version:
```
npm install xxx --save --save-exact
```
- 13
install latest minor version (using tilde)
``` 
~1.2.1
```
- 14
update packages
```
npm update (all)
npm update --dev
npm update --prod
```

#### 3
- 2
install from gist
```
npm install gist:4314adcd133c
```
- 3
install from folders
```
npm install ../xx
```
- 4
find registry. For example
```
www.npmjs.com/package/lodash
registry.npmjs.org/lodash
npm.im/lodash
```
- 5
search (not recommend)
```
npm search name
```

- 6
Pruning (delete non-listed packages)
```
npm list --depth 0
npm prune
npm prune --production
```

- 7
open official repo
```
npm repo name
```

- 8
updrade
```
npm i npm@latest -g
```

#### 4

- 1
Create a user account. Then
```
npm adduser
```

- 3
publish
After pushing your project to github, then
```
npm publish
```
check info
```
npm info name
npm repo name
```
Next we can add tag
```
git tag v1.0.1
git push --tags
```
- 4
update(3 steps)
1. change version in package.json, we need to execute
2.
```
npm version path (major,minor)
```
3. check
```
git tag
git push --tags
```

- 5
Alpha and Beta
1.change package.json like 1.0.0-beta.0 then
```
npm publish --tags beta
```

To install
```
npm install name@beta
```




