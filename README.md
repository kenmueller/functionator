# functionator

**Uncallable statements made callable**

## Download

```bash
npm i functionator
```

## Initialization

```javascript
const f = require('functionator')
```

## Usage

```javascript
document.querySelector('button').addEventListener('click', f(alert('hello')))
```

**Just wrap your statement with `f(...)`**

## Source code

```javascript
module.exports = f => () => f
```

**Yep, that's all!**