# Formulário animado com JS puro e CSS Animation

## Animation

8 propriedades:

- animation-name: animationname;
- animation-duration: 2s;
- animation-delay: 3s;
- animation-fill-mode: none;
- animation-play-state: running;
- animation-timing-function: ease;
- animation-direction: reverse;
- animation-iteration-count: infinite;

```css
@keyframes animationname {
  0% {
  }

  100% {
  }
}
```

podemos ter múltiplas animações no mesmo elemento

```css
.animate {
  animation: slide-top 2s, bounce 1s, fade 0.2s;
}
```

## References

[CSS Animation Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)

[Animation Timing Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function)

[Site para criar animações](http://animista.net/play/basic/scale-up)

[Site para criar cubic Bézier timming](https://matthewlein.com/tools/ceaser)
