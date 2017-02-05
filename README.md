How to publish a npm package
=====

1. cd project folder
2. create package.json
3. npm login
4. npm publish

If the package name has conflict with other existing packages, change the package name
or use a scoped name (@rp8@test).

Patch
=====
1. git add . && git commit 
2. npm version patch
3. npm publish
