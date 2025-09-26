# Se-ales-con-Transformada-de-Fourier
OBJETIVO DEL PROYECTO

El propósito de este proyecto es analizar señales en el dominio del tiempo y en el dominio de la frecuencia utilizando Python y la Transformada de Fourier. A través de este análisis, se busca entender cómo se representa una señal en ambos dominios y cómo se pueden identificar características importantes al aplicar la Transformada de Fourier (FFT).

Señales simuladas
Se trabajó con tres señales elementales:

Pulso rectangular: Señal con valores constantes en un intervalo y cero en el resto. Es útil para analizar la dispersión espectral.
Función escalón (Heaviside): Señal que cambia de 0 a 1 en un punto determinado. Representa un cambio abrupto y es común en sistemas de control.
Señal senoidal: Señal periódica que representa una sola frecuencia pura. Es clave para comprender cómo se comportan señales armónicas.
Para cada señal se generó:

Su representación en el dominio del tiempo.
Su espectro de frecuencia: magnitud y fase, usando np.fft.fft().
Herramientas usadas
Python 3.8+
NumPy para manejo de vectores y FFT.
Matplotlib para graficar las señales y espectros.
Git y GitHub para control de versiones y publicación del proyecto.
