# es-6-node-templates

- Husky & Lint-staged
```
npm i husky lint-staged


- Inside package.json


"husky": {
    "hooks": {
      "pre-commit": "lint-staged"
    }
  },
  "lint-staged": {
    "*.js": [
      "prettier --write",
      "eslint --fix src/",
      "pretty-quick — staged"
    ]
  }
```
