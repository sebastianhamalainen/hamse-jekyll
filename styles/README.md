# README #

### How do I use the mixins? ###

* go to your sass file e.g. ``` _frontpage.sass ```
* ### MAKE SURE YOU HAVE IMPORTED THE MIXINS FOLDER ``` @import "mixin/_mixin.sass" ```

### Mixins ###

These sass mixing will output

```
#!sass
.box
  +transition('background .5s ease-in-out')
  +border-radius(.4em)
```

this

```
#!css

.box {
  -webkit-transition: background .5s ease-in-out;
  -moz-transition: background .5s ease-in-out;
  -ms-transition: background .5s ease-in-out;
  -o-transition: background .5s ease-in-out;
  transition: background .5s ease-in-out;
  -webkit-border-radius: 0.4em;
  border-radius: 0.4em;
  background-clip: padding-box;
}
```