# Github Notebook preview does not open image redirection

On this 'Markdown preview', all images and texts will redirect well the user on 'https://google.com', but on the Notebookpreview of the file [test.ipynb](https://github.com/QuentinKlebaur/Notebook_preview_issue/blob/master/test.ipynb), it will not work properly

## html href img

<a href="https://google.com">
    <img src="https://github.com/QuentinKlebaur.png"/>
</a>

## html href text

<a href="https://google.com">
    Hello World !
</a>

## html href target _blank img

<a href="https://google.com" target="_blank">
    <img src="https://github.com/QuentinKlebaur.png"/>
</a>

## html href target _blank text

<a href="https://google.com" target="_blank">
    Hello World !
</a>

## html href target _parent img

<a href="https://google.com" target="_parent">
    <img src="https://github.com/QuentinKlebaur.png"/>
</a>

## html href target _parent text

<a href="https://google.com" target="_parent">
    Hello World !
</a>

## Markdown redirection img

[![redirect](https://github.com/QuentinKlebaur.png)](https://google.com)

## Markdown redirection text

[Hello World !](https://google.com)