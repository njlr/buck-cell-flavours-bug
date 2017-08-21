# buck-cell-flavours-bug

Demonstration of a bug in flavours across cells 🍦 🐛

```
buck --version
buck version 0391b98d8eae9587abefb0c2e86e2a227480a1aa
```


## Usage

This works:

```
buck run :app
```

But this does not:

```
buck run :app#debug
```

It appears that flavours do not carry through into cells!
