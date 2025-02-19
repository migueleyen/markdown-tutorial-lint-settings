# markdown lint settings

## manual cli fix

1. install package
`npm install -D markdownlint-cli2`

2.package.json

```
"scripts":
{
"mdlint:issues":"markdownlint-cli2 ./docs/fixed",
"mdlint
}
```

## auto onSave fix

1. install markdownlint extension

2..ui workspace setting
settings.json

```
{
    "[markdown]": {
        "editor.formatOnSave": true,
        "editor.codeActionsOnSave": {
            "source.fixAll.markdownlint": "explicit"
        }
    
    },
    
}
```
