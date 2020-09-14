
Writing in Markdown is _not that_ hard!

I **will** complete this lesson!

<!-- HEADINGS -->

# my title

## my title h2

### my title h3

#### my title h4

##### my title h5

###### my title h6

<!-- italic -->

This is an _italic_ text

this is an *italic* text

<!-- strong -->

this is an **strong** text

this is an ***strong italic*** text

<!-- italica y strong -->

this is an **_strong italic_** text

#### El simbolismo Colombiano en _Cien años de soledad_
Algunas palabras sobre el libro _Cien años_

<!-- strikethrough -->

Este es un ~~texto~~ tachado

<!-- UL -->

* apple
    * apple 2
* orange
    * asdfasdf
* etc

1. apple
2. orange
3. pinneapple

[serviciosmundoverde.com](http://www.serviciosmundoverde.com/)

[serviciosmundoverde.com](http://www.serviciosmundoverde.com/ "LO QUE DESEEN ESCRIBIR carajitos")

>This is a quote

---
___

` console.log('hello world') `

``` javascript
const fs = require('fs');
//const { require } = require('yargs');

let listadoPorHacer = [];

const guardarDB = () => {

    let data = JSON.stringify(listadoPorHacer);

    fs.writeFile('db/data.json', data, (err) => {

        if (err) throw new Error('No se pudo grabar', err);

    });

};

```

``` python
print("Hello world")
```

``` html
<h1>helloworld</h1>
```
![Visual studio code logo](vscode-450x450.png "vsc LOGO")


<!-- GITHUB MARKDOWN -->
* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [x] Task 4

@Ju4nc1t0 :smiley: :+1:






