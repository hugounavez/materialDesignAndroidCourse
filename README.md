# MaterialDesignAndroidCourse
El presente repositorio contiene los screens requeridos para la tarea de la primera semana del Curso de Desarrollo de Aplicaciones en Android por la Universidad Autónoma de México.

A partir de la imagen:

![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/o9aN7gWSEeaaqg5MSeYjIQ_521424d79698bfb8722baa94062502d9_revisionporpares1_Curso3.png?expiry=1510531200000&hmac=zUw4UVe4gCDM8Yl7JCwkkeY_GcPs7LZ7YxW0HdugFCY)

Se deben seleccionar los colores para la aplicación, que estén en armonía con la identidad corporativa de la imagen.

Se supone que el color primario, es el color que debe aparecer con mayor frecuencia en la aplicación. Y el secundario, el utilizado para acentuar algunos elementos/componentes en la pantalla como floating buttons y algunos otros widgets. Etc.

Como el color cyan es el que mas abarca en la imagen proporcionada del logotipo. He elegido este como color primario. El segundo elemento más común en la imagen es el marrón, pero a mi parecer que se ve un poco triste la aplicación, Así que elegí el naranja como color secundario.

No obstante, no estoy seguro de haber elegido correctamente los colores, agradezco cualquier comentario o sugerencia.

Aquí presento la imagen de la aplicación resultante y el fragmento de colores seleccionado:

![alt text](https://raw.githubusercontent.com/hugounavez/materialDesignAndroidCourse/master/firstScreenMaterialPalette.png)

El código es el siguiente:

```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <color name="colorPrimary">#00BCD4</color>
    <color name="colorPrimaryDark">#0097A7</color>
    <color name="colorAccent">#795548</color>
</resources>

```

La segunda opción, basándome más en la frecuencia de los colores de la imagen es la siguiente (solo mostraré el código):


```xml
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <color name="colorPrimary">#00BCD4</color>
    <color name="colorPrimaryDark">#0097A7</color>
    <color name="colorAccent">#FF5722</color>
</resources>

```
