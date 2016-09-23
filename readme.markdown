## quick usage


#### install
```
npm insall @jekrb/example-css
```

#### html

```html
<div class='example'>
   <h1>wow</h1>
   <p>coool</p>
</div>
```

#### scss

```css
@import '@jekrb/example-css/example'
```

#### build

```bash
node-sass --include-path ./node_modules scss/app.scss public_html/dist/app.css
```
