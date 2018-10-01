![DataOwl Logo](https://raw.githubusercontent.com/lucaswfh/dataowlweb/master/src/assets/img/Logo.png)

## Overview
Sera el repositorio centralizado de toda la documentacion del proyecto. En este repo se encontraran los Milestones y Labels para trackear los issues de cada entrega.

DATAOWL es una aplicación que inicialmente está pensada para uso dentro del campo de Automatización y Control Industrial, pero que puede ser modificada y extendida para usos más amplios. 

Se trata de una aplicacion que tendra por objetivo crear, actualizar y completar DataSets (conjunto de datos que tienen asignado algun tipo de clasificacion. Estos datos pueden ser escritos, multimedia, etc), que luego pueden ser usados para Machine Learning.

La aplicación se conecta a los componentes del teléfono (principalmente la cámara y la señal GPS), de modo que se pueda tomar una foto o grabar un video/audio en un lugar determinado, y guardar además la ubicación de donde fue realizada; entre otros datos (Que puede ser modificado para el requerimiento actual). 

En el caso del uso inicial que se le va a dar a la aplicacion, la foto en conjunto con la metadata de la misma, es luego enviada a los servidores backend para ser analizado por un analista de forma manual; y de esta forma completar un DataSet. Este DataSet luego sera utilizado en Machine Learning para generar un algoritmo, que en principio, se espera que sirva para la deteccion de automatica de malezas.

![Diagram](https://raw.githubusercontent.com/lucaswfh/dataowldocs/master/assests/img/Diagramv2.jpg)

 La particularidad de este aplicativo, es que no requiere Internet al momento de realizar la acción, ya que la información será guardada y enviada al momento en que la señal esté disponible.
También se realizará un acceso web al servidor, en donde los tecnicos y especialistas deberan ingresar para realizar la identificacion del contenido enviado de forma manual.

En la seccion de Wiki de este repositorio, se ira llenando la informacion de lo realizado para cada entrega (POC - Sprints) y en cada seccion de la aplicacion (Mobile, Backend y Web)


