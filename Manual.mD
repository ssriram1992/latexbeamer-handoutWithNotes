# How to use `handoutWithNotes`?

- Always start the file with 
```Tex
\usepackage{handoutWithNotes}
```
- For 1 slide and its notes on the right (in landscape mode)
```Tex
\pgfpagesuselayout{1 on 1 with notes landscape}[a4paper,border shrink=5mm]
```

- For 2 slides on left and two on right (in landscape mode) (Hail [Daniel Robinson's notes style](https://sites.google.com/site/danielprobinson/nonlinear-optimization-i) )
```Tex
\pgfpagesuselayout{2 on 1 with notes}[a4paper,border shrink=5mm]
```

- For one on one in portrait mode
```Tex
\pgfpagesuselayout{1 on 1 with notes}[a4paper,border shrink=5mm]
```
