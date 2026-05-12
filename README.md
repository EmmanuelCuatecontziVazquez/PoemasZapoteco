# PoemasZapoteco
Corpus de poemas del idioma Zapoteco

De acuerdo con la estructura propuesta, los datos se estrcturan de la siguiente manera

Corpus
├── Zapoteco
│   ├── verso1_poema1.txt
│   ├── verso2_poema1.txt
│   └── ...
├── Español
│   ├── verso1_poema1.txt
│   ├── verso2_poema1.txt
│   └── ...

Además esta el requisito de identificar correctamente la traducción correspondiente. Para ello podemos usar los metadatos de cada documento.
# propuesta de nomenclatura

idioma                E o Z
número de verso       1... n
id por poema, esto podría ser el nombre completo o solo indices según aparezcan, el problema es que de esta forma habría que establecer un orden,
también podemos usar nuestra inicial con un id numerico y de esa forma no habría solapamientos

ejemplo, para el 4to verso del 5to poema

Z4GK5.txt
E4GK5.txt
