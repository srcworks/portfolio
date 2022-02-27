# portfolio

convert to thumb:


```
cd assets/images
ls *.jpg|xargs -I {} convert -define jpeg:size=350x350 {} -thumbnail 350x350^ -gravity center -extent 359x350 previews/{}
```
