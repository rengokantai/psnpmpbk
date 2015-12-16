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
