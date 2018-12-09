## Graficador de grafos

### Instalación
Para la instalación primero, vamos a necesitar descargar py-gnuplot o `pip install py-gnuplot`, este paquete nos
va a permitir interactuar con *GnuPlot* desde Python.   

O también se puede instalar py-gnuplot manualmente:
```
wget http://downloads.sourceforge.net/project/gnuplot-py/Gnuplot-py/1.8/gnuplot-py-1.8.tar.gz
tar xzf gnuplot-py-1.8.tar.gz
cd gnuplot-py-1.8/
python setup.py install
```
Luego instalamos gnuplot con `sudo apt-get install gnuplot` o `dnf install gnuplot` en Fedora
o [compilándolo](https://sourceforge.net/projects/gnuplot/files/gnuplot/) con `./configure --enable-qt && sudo make clean install`.  
Observación: Debería instalarse con soporte para la terminal qt que viene incluído en el caso de instalarlo con `apt-get`.

### Para iniciarlo
`python gg.py nombre del archivo`  
Se puede mirar cualquiera de los archivos en el directorio "ejemplos" para entender el formato de entrada.

#### Pruebas
![alt text](/img/k8.png)
![alt text](/img/k2-3.png)  
![alt text](/img/r4.png)
![alt text](/img/butterfly.png)  
![alt text](/img/k1-12.png)
