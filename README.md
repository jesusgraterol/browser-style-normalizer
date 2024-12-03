# Browser Style Normalizer

The `browser-style-normalizer` is a stylesheet that resets all the browser's built-in styles, guaranteeing consistency across all major browsers.

It is important to note that this normalizer performs a hard style reset. If you are not using a robust CSS framework or component library, you should use a different normalizer.



<br/>

## Getting Started

Install the package:

```bash
npm install -S browser-style-normalizer
```

Include it in your main stylesheet:

```css
@import url('/node_modules/browser-style-normalizer/dist/index.css');
```





<br/>

## Built With

- CSS





<br/>

## License

[MIT](https://choosealicense.com/licenses/mit/)





<br/>

## Acknowledgments

- [CSS Tools: Reset CSS | Meyer Web](https://meyerweb.com/eric/tools/css/reset/)
- [A (more) Modern CSS Reset | Piccalilli](https://piccalil.li/blog/a-more-modern-css-reset/)
- [A Modern CSS Reset | Josh W Comeau](https://www.joshwcomeau.com/css/custom-css-reset/)
- [Preflight | Tailwind CSS](https://tailwindcss.com/docs/preflight)
- [Modern Normalize | Sindre Sorhus](https://github.com/sindresorhus/modern-normalize)
- [normalize.css](https://github.com/necolas/normalize.css)
- [sanitize.css](https://github.com/csstools/sanitize.css)
- [clean-css](https://github.com/clean-css/clean-css)





<br/>

## Deployment

Install dependencies:
```bash
npm install
```

Build the stylesheet:
```bash
npm start
```

Publish to `npm`:
```bash
npm publish
```
