## Visualization 

For visualization 3d model run web  in root folder:
```bash
    python3 -m http.server 1337
```
and run in your browser
```url
    http://0.0.0.0:1337/public/
```
or 
```url
    http://0.0.0.0:1337/public/#../../data/realty3d/724/72488/7248864/1514442_w0.png,../../data/realty3d/724/72488/7248864/1514442_w3.png,../../data/realty3d/724/72488/7248864/1514442.mtl,../../data/realty3d/724/72488/7248864/1514442_f0.png,../../data/realty3d/724/72488/7248864/1514442.obj,../../data/realty3d/724/72488/7248864/1514442_w1.png,../../data/realty3d/724/72488/7248864/1514442_w2.png|../../data/realty3d/724/72488/7248864/1514440_w2.png,../../data/realty3d/724/72488/7248864/1514440.mtl,../../data/realty3d/724/72488/7248864/1514440_w0.png,../../data/realty3d/724/72488/7248864/1514440.obj,../../data/realty3d/724/72488/7248864/1514440_w1.png,../../data/realty3d/724/72488/7248864/1514440_f0.png,../../data/realty3d/724/72488/7248864/1514440_w3.png|../../data/realty3d/724/72488/7248864/1514441_w2.png,../../data/realty3d/724/72488/7248864/1514441_w1.png,../../data/realty3d/724/72488/7248864/1514441_w0.png,../../data/realty3d/724/72488/7248864/1514441_f0.png,../../data/realty3d/724/72488/7248864/1514441.obj,../../data/realty3d/724/72488/7248864/1514441.mtl,../../data/realty3d/724/72488/7248864/1514441_w3.png|../../data/realty3d/724/72488/7248864/1514443.mtl,../../data/realty3d/724/72488/7248864/1514443_w0.png,../../data/realty3d/724/72488/7248864/1514443_w2.png,../../data/realty3d/724/72488/7248864/1514443_f0.png,../../data/realty3d/724/72488/7248864/1514443.obj,../../data/realty3d/724/72488/7248864/1514443_w3.png,../../data/realty3d/724/72488/7248864/1514443_w1.png
```
or in Jupyter
```python
from IPython.display import IFrame

IFrame(src='http://0.0.0.0:1337/#../../data/realty3d/724/72488/7248864/1514442_w0.png,../../data/realty3d/724/72488/7248864/1514442_w3.png,../../data/realty3d/724/72488/7248864/1514442.mtl,../../data/realty3d/724/72488/7248864/1514442_f0.png,../../data/realty3d/724/72488/7248864/1514442.obj,../../data/realty3d/724/72488/7248864/1514442_w1.png,../../data/realty3d/724/72488/7248864/1514442_w2.png|../../data/realty3d/724/72488/7248864/1514440_w2.png,../../data/realty3d/724/72488/7248864/1514440.mtl,../../data/realty3d/724/72488/7248864/1514440_w0.png,../../data/realty3d/724/72488/7248864/1514440.obj,../../data/realty3d/724/72488/7248864/1514440_w1.png,../../data/realty3d/724/72488/7248864/1514440_f0.png,../../data/realty3d/724/72488/7248864/1514440_w3.png|../../data/realty3d/724/72488/7248864/1514441_w2.png,../../data/realty3d/724/72488/7248864/1514441_w1.png,../../data/realty3d/724/72488/7248864/1514441_w0.png,../../data/realty3d/724/72488/7248864/1514441_f0.png,../../data/realty3d/724/72488/7248864/1514441.obj,../../data/realty3d/724/72488/7248864/1514441.mtl,../../data/realty3d/724/72488/7248864/1514441_w3.png|../../data/realty3d/724/72488/7248864/1514443.mtl,../../data/realty3d/724/72488/7248864/1514443_w0.png,../../data/realty3d/724/72488/7248864/1514443_w2.png,../../data/realty3d/724/72488/7248864/1514443_f0.png,../../data/realty3d/724/72488/7248864/1514443.obj,../../data/realty3d/724/72488/7248864/1514443_w3.png,../../data/realty3d/724/72488/7248864/1514443_w1.png
```
