# canvas-progress-bar

a progress-bar created with canvas.

code taken from this [tutorial](http://www.splashnology.com/article/how-to-create-a-progress-bar-with-html5-canvas/478/)

``` js
var bar = requrie('canvas-progress-bar')

bar.progess(0.8) //80%

//bar is a canvas element that you can add to the DOM.
document.body.appendChild(progess)
```
or, if running in nodejs

```
bar.pngStream().pipe(fs.createWriteStream('progress.png'))
```

the progress bar looks like this:

![50%](https://raw.github.com/dominictarr/canvas-progress-bar/master/progress.png)


## License

MIT
