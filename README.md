Recherche sémantique par texte dans des corpus d'images.

Des parties du code (collecte) proviennent de [ModOAP](https://github.com/MODOAP/Telechargement-documents-Gallica)

## Types de datasets pris en charge (CSV):

**Liste d'identifiants Arks (Gallica) :**
| ark |
| --- |
| bpt6k9818982g |
| bpt6k34118531 |
| ... | 
| bpt6k9819151g |

**Images locales légendées :**\
La colonne *legend* est optionnelle
| local_image | legend |
| --- | --- | 
| C:\absolute\path\to\image1.jpg | Légende de l'image 1 |
| C:\absolute\path\to\image2.jpg | Légende de l'image 2 |
| ... | ... |
| C:\absolute\path\to\image250.jpg | Légende de l'image 250 |

**Images distantes légendées :**\
La colonne *legend* est optionnelle
| image | legend |
| --- | --- | 
| [https://gallica.bnf.fr/iiif/ark:/12148/bpt6k9818982g/f8/250,732,1404,1170/full/0/native.jpg](https://gallica.bnf.fr/iiif/ark:/12148/bpt6k9818982g/f8/250,732,1404,1170/full/0/native.jpg) | Légende de l'image 1 |
| [https://gallica.bnf.fr/iiif/ark:/12148/bpt6k9818982g/f9/862,820,707,917/full/0/native.jpg](https://gallica.bnf.fr/iiif/ark:/12148/bpt6k9818982g/f9/862,820,707,917/full/0/native.jpg) | Légende de l'image 2 |
| ... | ... |
| [https://gallica.bnf.fr/iiif/ark:/12148/bpt6k9818982g/f10/235,566,711,1170/full/0/native.jpg](https://gallica.bnf.fr/iiif/ark:/12148/bpt6k9818982g/f10/235,566,711,1170/full/0/native.jpg) | Légende de l'image 250 |

## Dataset de test (EyCon project)[https://eycon.huma-num.fr/s/fr/page/corpora]:
| Fichier d'indexs | Dossier d'images |
| --- | --- |
| [eycon.smantic](https://drive.google.com/file/d/1KvUDA5HsD4cWNz5fpZsMjrMpadfcOlsZ/view?usp=sharing)  | [Images EyCon](https://drive.google.com/drive/folders/1atmTvp8_G_uhUzXxVcTjsty_TPi2XPmc?usp=sharing) |
