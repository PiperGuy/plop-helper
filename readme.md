## 💧 plop-helper

<a href="https://npmjs.com/package/@piperguy/plop-helper">
    <img alt="npm" src="https://img.shields.io/npm/v/plop-helpe.svg?style=flat-square">
</a>

<a href="https://npmjs.com/package/@piperguy/plop-helper">
    <img alt="npm" src="https://img.shields.io/npm/dt/@piperguy/plop-helper?style=flat-square">
</a>

_A [plop][plop] helper to generate topic icons._

### 📦 Installation

This package is installable from [npm][npm].

```bash
npm install --save-dev @piperguy/plop-helper
```

### 🥑 Usage

Before you can use the `plop-pack`, you have to load it into the `plop` object.

```javascript
plop.load("@piperguy/plop-helper")
```

Once loaded, you now have access the following helpers.

#### `icon`

This helper is very specific to [piperguy.github.io][piperguy]. It generates an icon given a topic.

**input**

```javascript
{
    topic: "coding"
}
```

**helper**

```handlebars
{{icon topic}}
```

**output**

```javascript
"💻"
```

### ❔ Questions

🐛 report bugs by filing [issues][issues]  
📢 provide feedback with [issues][issues] or on [twitter][twitter]

[plop]: https://plopjs.com
[npm]: https://npmjs.com
[piperguy]: https://piperguy.github.io
[issues]: https://github.com/piperguy/plop-helper/issues
[twitter]: https://twitter.com/_PiperGuy_
