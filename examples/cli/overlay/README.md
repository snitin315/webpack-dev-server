# CLI: --client-overlay option

```shell
npm run webpack-dev-server -- --open --client-overlay
```

## What Should Happen

1. The script should open `http://localhost:8080/` in your default browser.
2. You should see an overlay in browser for compilation errors.
3. Update `entry` in webpack.config.js to `app.js` and save.
4. You should see the text on the page itself change to read `Success!`.
