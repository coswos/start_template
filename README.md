template with connected SASS
```bash
sass --watch styles.scss styles.css
```
you need turn on watcher for online rewrite css through SASS preprocessor

OR
you can do it manually with next commands
```bash
sass styles.scss styles.css
```

IF
you need fast loading in production version you can use 
```bash
sass --style=compressed styles.scss:styles.css
```

