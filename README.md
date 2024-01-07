<h3 align="center">Olá ✌️</h3>



<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/alysiaa/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/alysiaa/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/alysiaa/snk/output/github-contribution-grid-snake.svg"
  />
</picture>





[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L26-L33)

If you are only interested in generating a svg, consider using this faster action: `uses: Platane/snk/svg-only@v3`

**dark mode**

For **dark mode** support on github, use this [special syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) in your readme.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```

**interactive demo**

<a href="https://Alysiaa.github.io/snk">
  <img height="300px" src="https://user-images.githubusercontent.com/1659820/121798244-7c86d700-cc25-11eb-8c1c-b8e65556ac0d.gif" ></img>
</a>

[platane.github.io/snk](https://Alysiaa.github.io/snk)

**local**

```
npm install

npm run dev:demo
```
