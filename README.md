# portfolio


Notes to self:

* convert to thumbnails:


```
cd assets/images
ls *.jpg|xargs -I {} convert -define jpeg:size=350x350 {} -thumbnail 350x350^ -gravity center -extent 350x350 previews/{}
```
