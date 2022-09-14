
![Banner](https://github.com/yromariogh/IA2-Recovery/banner.png)

# Ajuste de la calibración durante la recuperación en el sistema óptico CASSI

## Integrantes:
Yesid Romario Gualdrón Hurtado (2190052), Ruben Dario Rodríguez Moreno (2181968), Julian Garcia (218...)
  
## Objetivo principal:
  * Reconstrucción de imágenes espectrales capturadas con el sistema óptico CASSI considerando el desajuste propio del hardware, mediante redes neuronales profundas.

### Objetivos secundarios:
  * Analizar las diferentes arquitecturas e hiperparámetros que permitan aumentar el PSNR de las reconstruciones.
  * Corregir el desajuste del sistema óptico CASSI, mediante el ajuste de hiperparámetros y la exploración de distintos enfoques.


## Dataset:
1. Dataset con 14 imágenes espectrales de 512x512x24 capturadas en laboratorio de óptica HDSP, se tienen también sus correspondientes medidas comprimidas de 512x535.
         https://drive.google.com/drive/folders/177ePldd0ABKVCXvBtF7WvvZ9OldBA2Wh?usp=sharing
2. Dataset NTIRE ARAD 2020 de dominio público con dimensiones 256x256x31, usado para la simulación de captura (256x286) y variación de niveles de degradación.
         https://drive.google.com/drive/folders/1vPGg8IWcvUWeUlDdyLtlFLgO_l2vJLuf?usp=sharing 
         
## Modelos:
  * Se hizo uso de arquitecturas UNet, Convolutional Autoencoders, RNNs y CNNs.

## Enlaces:
  * Codigo: https://colab.research.google.com/drive/
  * Video: https://www.youtube.com/watch?v=
  * Repositorio: https://github.com/yromariogh/IA2-Recovery
