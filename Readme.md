# Rejoice clone website 

original web link: https://www.rejouice.com/

master branch handle by -> computer

- we will convert font size WOFF2  ->   TTF 
then your font are work


- how to add font famaly to custom 

```
@font-face {
    font-family: nb;
    /* src:url(./download/NBInternationalProBoo.ttf) */
    src:url('./download/Rejouice-Headline.ttf')
}
```
And 

```
* {
  padding: 0px;
  margin: 0px;
  /* font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; */
  font-family: nb;
  box-sizing: border-box;

}
```