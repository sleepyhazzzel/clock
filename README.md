## Clock
- Background-color: `#def`
- Light Ball color: `#42abff`, `#6bc33c`, `#ff6296`, `#ffeb3b`
- Inward text is made by css style --> background-clip

```css
.time>p {
    display: inline;
    font: 600 100px 'Roboto Mono', monospace;
    background-color: rgb(120, 150, 175);
    color: transparent;
    text-shadow: 2.5px 2.5px 3px rgba(255, 255, 255, 0.6);
    -webkit-background-clip: text;
    -moz-background-clip: text;
    background-clip: text;
    line-height: 15vh;
    letter-spacing: -3px;
}
```

### Reference
1. [Neumorphism](https://www.youtube.com/watch?v=8CuUUOOO2ms&t=98s)
2. [Lighting Ball Effect](https://www.youtube.com/watch?v=k3eEk8iUCE4&t=156s)
