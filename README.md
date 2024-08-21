# my-simple-app-that-uses-private-npm-package

```bash
npm install # it will not work, missing github token

TOKEN_PRIVATE_REGISTRY_GITHUB_PACKAGES=xxx npm install # it will work! the github token needs the permission "read:packages"
```
