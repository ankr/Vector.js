# Vector.js

Simple "immutable" vector class.

# Installation

# 1. Access Token
Create a [*Personal Access Token*](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token) with *repo* and *read:packages* permissions.

# 2. Login to registry
Login with the scope _ankr_.
```
npm login --scope=@ankr --registry=https://npm.pkg.github.com
Username: YOUR_GITHUB_USERNAME
Password: YOUR_PERSONAL_ACCESS_TOKEN
Email: (this IS public) YOUR_EMAIL
```

# 3. Install package
```
npm install @ankr/vector.js
```

# Usage
```
import Vector, { TAU } from './node_modules/@ankr/vector.js/index.js';

console.log(TAU, Vector);
```
