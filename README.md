# webpack-bootstrap-alpine

Sample repository bundling Bootstrap 5 and Alpine JS.

## Starting

```bash
> npm install
> npm run build
> python -m http.server
```

Running `npm run build` will build the minified css and js assets.
You can customize the bootstrap theme by editing `src/scss/styels.scss` to override variables
in `node_modules/bootstrap/scss/_variables.scss`.
Check out the [bootstrap customizataion doc](https://getbootstrap.com/docs/5.0/customize/overview/) for more details.

