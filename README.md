# Wichtelbuch - Python

Hallo & willkommen beim Wichtelbuch!
Oder genauer gesagt bei der README.md :D

Das eigentliche Buch liegt in einem sogenannten *Notebook*.
Um ein Notebook zu öffnen brauchst du [Jupyter](https://jupyter.org/).

Jupyter ist fast schon eine IDE, wobei *interaktiver Editor* es besser trifft.
Um Jupyter zu installieren brauchst du nur folgenden Befehl und Python bzw. `pip`:
```
pip install jupyterlab
```

Sollte pip nicht installiert sein, kann Python es auch selber installieren mit:
```
python -m ensurepip
```

## Starten von Jupyter

Unter Linux kannst du Jupyter ganz einfach über das Terminal starten.

```
jupyter lab
```
Auf Windows ist das bisschen *umständlicher* weil jupyter nicht im PATH liegt, bzw Windows weiß nicht wo die .exe liegt.
Deshalb muss man folgenden Befehl ausführen:
```
python -m notebook
```
Danach öffnet sich in deinem Browser ein neuer Tab, allerdings bei der URL [http://localhost:8888/tree](http://localhost:8888/tree).
Das benutzt ein älteres Interface, wir wollen allerding das neuere und coolere Lab.
Das findest du unter [http://localhost:8888/lab](http://localhost:8888/lab).

## Aktuelle Version

```
git clone https://github.com/gSys1337/wichtel.git
```
Damit kannst du über das Terminal die aktuelle Version erhalten.
Alternativ direkt über [GitHub](https://github.com/gSys1337/wichtel.git).
