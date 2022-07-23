<h1>Menciones-Twitter</h1>
<p>Programa que en base a un usuario (id), recolecta sus 100 últimos Tweets, considerese como Tweet cada RT o Tweet escrito por la persona.<br>
Una vez que se recolectan los Tweets, los filtra por los que no son un RT, de esta forma solo quedan Tweets dichos por el usuario.<br></p>

<h3>Parámetros</h3>

<p>Donde <b>inserte_token</b> es obligatorio y corresponde a un bearer_token sacado de <a href="https://developer.twitter.com/en">Twitter Developer</a></p>

```diff
- bearer_token = "inserte_token"
```

<p><b>user_id</b> debe ser el id de un usuario, para ello se recomienda utilizar <a href="https://tweeterid.com/">Tweeter id</a></p>

```python
user_id = 2754746065
word = "Gigante Noble" #Palabra a buscar
```
<h2>Ejemplo utilizado</h2>
<p>Como base se toma el id <b>'123955962'</b> correspondiente a Kast, y como palabra a buscar <b>'Boric'</b>.<br>
Para la fecha del scrapeo de datos <b>23/07/2022</b>, algunos resultados fueron:<br><br>
Tweets con menciones a Boric:  <b>18</b><br> 
Tweets sin menciones a Boric:  <b>57</b><br>
De un total de: <b>75 tweets</b>; los <b>25</b> restantes corresponden a <b>RT</b><br>

Lo cual se ve representado en una gráfica al final de <a href="https://github.com/alexbgh1/Menciones-Twitter/blob/main/menciones.ipynb">menciones.ipynb</a></p>
![alt text](https://github.com/alexbgh1/Menciones-Twitter/blob/main/img/img_reference.png)

<h2>El material utilizado como plantilla</h2>
<p>El código como plantilla para la obtención de datos utilizando API de Twitter y conversión a archivo csv corresponde a <a href="https://github.com/matthieuvernier">Matthieu Vernier</a><br>
<a href="https://www.youtube.com/watch?v=giyYEZB7XOI&ab_channel=InstitutodeInformaticaUACh">Source video</a> <br> <a href="https://github.com/matthieuvernier/INFO133_2022">Source code</a></p>
