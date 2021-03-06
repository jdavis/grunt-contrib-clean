# Usage Examples

There are three formats you can use to run this task.

## Short

```js
clean: ["path/to/dir/one", "path/to/dir/two"]
```

## Medium (specific targets with global options)

```js
clean: {
  build: ["path/to/dir/one", "path/to/dir/two"],
  release: ["path/to/another/dir/one", "path/to/another/dir/two"]
},
```

## Long (specific targets with per target options)

```js
clean: {
  build: {
    src: ["path/to/dir/one", "path/to/dir/two"]
  }
}
```
## Force (specific targets with force option)

```js
clean: {
  build: {
    src: ["path/to/dir/one", "path/to/dir/two"]
    options: {
        force: true
    }
  }
}
```

## Quiet (specific targets with quiet option)

```js
clean: {
  build: {
    src: ["path/to/dir/one", "path/to/dir/two"]
    options: {
        quiet: true
    }
  }
}
```
