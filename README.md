# Task-Jade

Compiles and watches Jade-files.


## Configurations

##### rootFile

The index file of you project.


##### output

Glop for the destination of fonts.

##### watch

Glop for watcher.


*Example:*

```
{
  rootFile: './src/index.jade',
  output: dest,
  watch: sources.jade /* "./src/**/*.jade" */
}
```


## Dependencies

- gulp-plumber
- gulp-watch
- gulp-jade

Either install dependencies within this task, or type ``npm install --save-dev [dependencies]``.
