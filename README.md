# Light-weight Lazy Image Loading on Scroll

Lazy load ```<img>``` or background-images on image scroll.

In your HTML image tag just add data-image e.g:

```
<img src="lowres.jpg" data-image="mainimage.jpg" />
```

and using inline background-image style just add data-background:

```
<div style="background-image: url('lowres.jpg');" data-background="mainimage.jpg"></div>
```
