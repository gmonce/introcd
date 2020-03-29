## Ambiente de desarrollo

#### **Curso Introducción a la Ciencia de Datos**

Facultad de Ingeniería - Universidad de la República

En este documento se presentan las indicaciones para generar el ambiente de trabajo que se utilizará durante el curso para los desarrollos que se realicen. Sugerimos a los estudiantes instalar las herramientas aquí presentadas, para facilitar el desarrollo de las tareas que se indiquen durante  el curso, y para luego realizar el trabajo final. 

El ambiente está compuesto por entornos y herramientas muy populares, todas de código abierto, que permiten el desarrollo tanto en Python como en R. 

### Primer paso: instalar Anaconda. 

Anaconda es una distribución de Python y R pensada especialmente para desarrollos de Ciencia de Datos. Incluye (o permite desargar) múltiples paquetes de computación científica que ya vienen por defecto. Viene con un gestor de instalaciones, ambientes y dependencias llamado *conda* muy fácil de utilizar. 

Anaconda y sus paquetes están disponible para todas las plataformas (Linux, Windows, Mac OS X). 

Para instalar Anaconda, descárgue la versión para Python 3.7 correspondiente a su Sistema Operativo [aquí](https://www.anaconda.com/distribution/#download-section).  Una vez instalado, hay dos formas principales de acceder:

- Vía la línea de comandos, utilizando conda
- Vía un navegador gráfico llamado Anaconda Navigator. 

Para verificar que ha instalado correctamente la distribución o para actualizar la distribución a las últimas versiones, abra una terminal, y ejecute los comandos:

\$ conda update conda

\$ conda update anaconda

Links adicionales:
- [Anaconda Individual Edition](https://docs.anaconda.com/anaconda/)
- [Conda user guide](https://conda.io/projects/conda/en/latest/user-guide/index.html)

### Segundo paso: instalar los componentes de R esenciales

Por defecto, Anaconda no incluye el intérprete y los paquetes principales de R, así que debemos instalarlos. Como ya tenemos conda, lo utilizamos:

\$ conda install r-base r-essentials

- [Lista de paquetes disponibles para R](https://docs.anaconda.com/anaconda/packages/r-language-pkg-docs/)

### Tercer paso: probar los Jupyter Notebooks

Los notebooks de Jupyter son una herramienta de código abierto que permiten crear documentos que incluyen código ejecutable, así como visualizaciones, ecuaciones, y texto. Permiten experimentar fácilmente, y distribuir en forma conjunta análisis realizados y los comentarios asociados, así como reproducirlos por parte de quien los recibe. En principio, los documentos e informes utilizados en este curso serán todos Jupyter Notebooks. El nombre Jupyter surge de Julia, Python y R, tres de los principales lenguajes de programación utilizados en la Ciencia de Datos. 

Para ejecutar un notebook de Jupyter, ir al directorio donde existe el notebook (la extensión de los notebooks es .ipynb) y ejecutar

\$ jupyter notebook

Esto creará un servidor, y probablemente abra un link en su navegador para poder acceder a una visión de los directorios con los archivos. Si no lo abre, el notebook queda corriendo en esta dirección local:

http://localhost:8888/tree

La nueva interfaz para los notebooks se llama Jupyter Lab, y presenta varias innovaciones para facilitar el uso. Para acceder a Jupyter Lab, utilizando el mismo servidor, basta con acceder a la dirección:

http://localhost:8888/lab

(también es posible, para ejecutar los notebooks bajo Jupyter lab, ejecutar directamente "jupyter lab" en la línea de comandos al comienzo).

Los notebooks de Jupyter presentan varias facilidades para programar en entornos interactivos, permitiendo documentos "vivos", donde es posible inspeccionar el ambiente de desarrollo, realizar pruebas, documentar (utilizando los lenguaajes [Markdown](https://opensource.com/article/19/9/introduction-markdown) e incluso [fórmulas](https://www.overleaf.com/learn/latex/mathematical_expressions) al estilo LaTeX), incluir imágenes, etc. 

Por más información, consultar la [documentación](https://jupyter-notebook.readthedocs.io/en/stable/) o uno de los miles de tutoriales que hay en Internet. 

Un aspecto interesante de los Notebooks de Jupyter es que github los visualiza automáticamente. 

### Cuarto paso: verificar que podemos programar en R y Python en nuestros notebooks.

Para esto, utilice Jupyter Lab, y cree un nuevo documento. La interfaz deberá ofrecerle la opción de crear un notebook de R o de Python. En el mismo directorio que este documento están los Notebooks [HelloR.ipynb](HelloR.ipynb) y [HelloPython.ipynb](HelloPython.ipynb). Intente abrirlos y ejecutar el código. Si no tiene errores, usted tiene seguramente el ambiente configurado para empezar a trabajar.

**Bienvenidos al curso de Introducción a la Ciencia de Datos** 
