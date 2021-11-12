Resources: https://.icomoon.io/

## Mask

What is actually a mask ?
* Basically a mask defines an area where can see look through the element and see what's behind that element.

### Figure Element
* Are great for some text and descriptions of the images.

### Some browser not supported by "mask"
* This code can use to support mask in some browser
```
//Older browser

    background-image: url(../img/chevron-thin-right.svg);
    background-size: cover;

//Newer Browser - mask

    @supports (-webkit-mask-image: url()) or (-webkit-mask-image: url())    
      background-color: var(--color-primary);
      -webkit-mask-image: url(../img/chevron-thin-right.svg);
      -webkit-mask-size: cover;
      mask-image: url(../img/chevron-thin-right.svg);
      mask-size: cover;
      background-image: none;
```


### Build Process
```
diane@Dianes-MacBook-Air starter % npm run build:css
```