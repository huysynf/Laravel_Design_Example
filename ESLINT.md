# instal eslint homepage: https://eslint.org/docs/user-guide/getting-started
```bash
npm install eslint --save-dev

# or

yarn add eslint --dev

# init 
eslint init

```
# example config use json : file name: .eslintrc.json

```json

{
    "env": {
        "browser": true,
        "es2021": true,
        "node": true
    },
    "extends": [
        "eslint:recommended",
        "plugin:react/recommended"
    ],
    "parserOptions": {
        "ecmaFeatures": {
            "jsx": true
        },
        "ecmaVersion": 12,
        "sourceType": "module"
    },
    "plugins": [
        "react"
    ],
    "settings": {
        "react": {
            "version": "detect"
        }
    },
    "rules": {
        "react/no-unescaped-entities": 0
    }
}

```

# example eslint ignore

```text
file name: .eslintignore

config: 

src/reportWebVitals.js
src/assets
src/setupTests.js
src/*Test.js
public
build

```
