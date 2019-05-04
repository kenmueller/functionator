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

## Source code

```javascript
export default f => f
```

**Yep, that's all!**