# Python Data Science Template



Doc: https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

sudo apt-get install python3-dev

(ojo, que aparezca el 3).

Datasets: 
https://grouplens.org/datasets/movielens/



## Workflow:

### Instalación:

- Necesario tener el pip3 y recomendable el python3.6 al menos.
- Ejecutar ./createEnv.sh
- Ejecutar ./activate.sh
- Ejecutar ./install.sh

### Activar el entorno

- Ejecutar ./activate.sh



### PyCharm

- Ejecutar el PyCharm y crear nuevo proyecto. Indicarle que use Existing Interpreter, marcarle Virtualenv y marcarle el path dentro de env/bin/python3.



### Notas

- A veces la activación del environment falla sin decir nada. Debe aparecer un (env) en el prompt. Si no aparece, ir manualmente al directorio env/bin y ahí hacer el source activate

- Si falla el install.sh, usar el altInstall.sh...

- Lección 5 y 6 de Spark podrían complementarse. En la lección 5 se usa SQL, pero de una forma tosca se construyen los dataframes (a partir de RDDs). En la lección 6 se levantan los dataframes de forma más natural, aunque no tiene consultas SQL.

- SparkContext es para RDDs en general... SparkSession es para DataFrames.


