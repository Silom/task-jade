# Task-Jade

Compiles and watches Jade-files.


*TODO npm install here :/*


## Configurations

##### rootFile

The index file of you project.

##### output

Glop for the destination of the html.

##### watch

Glop for watcher.


*Example:*

```
{
  rootFile: './src/index.jade',
  output: dest,
  watch: './src/**/*.jade'
}
```

### Advanced

Add this line to your gulp object:

```
gulp.isProduction = true
```

The html is rendered pretty as default, with the production flag it gets minified.
