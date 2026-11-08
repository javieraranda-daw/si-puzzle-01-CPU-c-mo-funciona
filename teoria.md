# Teoría · Pieza NN: Nombre de la pieza

**Grupo:** Nombre Apellido · Nombre Apellido

> Máximo 1 folio por las dos caras. Es lo que estudiará toda la clase para el test: claro, exacto y sin relleno.

## Conceptos clave

* **CPU:** Procesador principal y «cerebro» del ordenador encargado de interpretar instrucciones y ejecutar cálculos.
* **Arquitectura de Von Neumann:** Modelo teórico donde los datos y las instrucciones del programa comparten el mismo espacio en memoria principal.
* **ALU (Unidad Aritméticológica):** Componente que realiza operaciones matemáticas (sumas, restas) y lógicas (comparaciones).
* **Unidad de Control (UC):** Bloque que extrae las instrucciones de la memoria, las decodifica y coordina al resto del sistema.
* **Registros:** Pequeñas celdas de almacenamiento interno de ultra alta velocidad para datos de uso inmediato.
* **Ciclo de instrucción:** Secuencia continua que realiza la CPU dividida en tres fases: captación (*Fetch*), decodificación (*Decode*) y ejecución (*Execute*).
* **CISC:** Arquitectura de conjunto de instrucciones complejo (estándar x86 de Intel/AMD para alto rendimiento).
* **RISC:** Arquitectura de conjunto de instrucciones reducido (estándar ARM enfocado a eficiencia energética).
* **Thermal Throttling:** Mecanismo de protección donde la CPU reduce su velocidad automáticamente al sobrecalentarse.

---

## Tabla resumen

| Tipo | Dato clave | Cuándo se usa |
| :--- | :--- | :--- |
| **CISC (x86)** | Instrucciones complejas, varios ciclos de reloj. | Ordenadores de sobremesa, portátiles de rendimiento y servidores. |
| **RISC (ARM)** | Instrucciones simples ejecutadas en un ciclo. | Smartphones, tablets y portátiles de bajo consumo (ej. Apple Silicon). |
| **Memoria Caché** | Memoria ultra rápida integrada (L1, L2, L3). | Almacenar datos frecuentes para evitar accesos lentos a la RAM. |

---

## Datos que hay que saberse

* La CPU funciona repitiendo millones de veces por segundo el ciclo: **Captación $\rightarrow$ Decodificación $\rightarrow$ Ejecución**.
* Los valores de frecuencia de reloj se miden en **GHz** (gigahercios) y determinan los ciclos por segundo.
* El consumo y calor disipado se miden mediante el **TDP** en vatios (W).
* Un **zócalo (socket)** incompatible físico o de chipset impide conectar la CPU a la placa base.

---

## Preguntas tipo test (8)

1. **¿Cuál es la función principal de la Unidad Aritméticológica (ALU)?**
   - a) Coordinar el tráfico de los buses del sistema.
   - b) Realizar cálculos matemáticos y operaciones lógicas. ← correcta
   - c) Almacenar permanentemente el sistema operativo.
   - d) Traducir el código fuente a lenguaje ensamblador.
   - *Explicación:* La ALU es el motor de cálculo del procesador encargado estrictamente de las operaciones aritméticas y lógicas.

2. **¿En qué consiste la arquitectura de Von Neumann?**
   - a) En separar físicamente la memoria de datos y la de instrucciones en chips distintos.
   - b) En que los datos y las instrucciones del programa comparten el mismo espacio de memoria principal. ← correcta
   - c) En utilizar exclusivamente instrucciones reducidas de un solo ciclo.
   - d) En eliminar por completo los registros internos de la CPU.
   - *Explicación:* El modelo teórico de Von Neumann se caracteriza por utilizar una única memoria principal compartida tanto para las instrucciones como para los datos.

3. **¿Cuáles son las tres fases del ciclo de instrucción de una CPU en orden correcto?**
   - a) Ejecución, Captación, Decodificación.
   - b) Decodificación, Ejecución, Captación.
   - c) Captación, Decodificación, Ejecución. ← correcta
   - d) Almacenamiento, Procesamiento, Salida.
   - *Explicación:* El ciclo estándar de la CPU siempre comienza capturando la instrucción, pasa por decodificarla en la UC y finaliza ejecutándola.

4. **¿Qué diferencia fundamental existe entre las arquitecturas CISC y RISC?**
   - a) CISC usa instrucciones complejas y RISC instrucciones reducidas y simples. ← correcta
   - b) RISC solo se usa en ordenadores de sobremesa y CISC en teléfonos móviles.
   - c) CISC no utiliza memoria caché y RISC sí.
   - d) No existe ninguna diferencia en su conjunto de instrucciones.
   - *Explicación:* CISC prioriza instrucciones complejas (x86) mientras que RISC prioriza un conjunto reducido y rápido para optimizar energía (ARM).

5. **¿Qué indica el parámetro TDP (Thermal Design Power) en una CPU?**
   - a) La velocidad máxima en gigahercios a la que puede hacer overclock.
   - b) La cantidad de memoria caché L3 integrada en el chip.
   - c) El consumo energético máximo estimado y el calor disipado que el sistema de refrigeración debe soportar. ← correcta
   - d) El número exacto de hilos de procesamiento multitarea.
   - *Explicación:* El TDP mide la potencia térmica de diseño en vatios, indicando el calor máximo que debe disipar el disipador.

6. **¿Qué provoca el fenómeno conocido como *Thermal Throttling*?**
   - a) Una bajada de rendimiento de la CPU provocada automáticamente para evitar daños por sobrecalentamiento. ← correcta
   - b) Un fallo de incompatibilidad al colocar el procesador en el zócalo de la placa base.
   - c) La rotura física de los pines del procesador durante el montaje.
   - d) Un cuello de botella generado por una tarjeta gráfica muy antigua.
   - *Explicación:* Cuando la temperatura sube demasiado, el procesador reduce su velocidad de reloj por seguridad para enfriarse.

7. **¿Qué función cumplen los registros internos dentro de una CPU?**
   - a) Almacenar los archivos a largo plazo como un disco duro SSD.
   - b) Servir como celdas de almacenamiento ultrarrápidas de uso inmediato para la CPU. ← correcta
   - c) Suministrar energía eléctrica estable desde la fuente de alimentación.
   - d) Mostrar las imágenes generadas por el sistema en el monitor.
   - *Explicación:* Los registros son pequeñas memorias internas de máxima velocidad que guardan datos temporales durante la ejecución de las instrucciones.

8. **¿Qué es un «cuello de botella» en un equipo informático relacionado con la CPU?**
   - a) Un defecto de fábrica en los pines del zócalo del procesador.
   - b) Una limitación de rendimiento donde un componente lento (ej. gráfica vieja) frena la potencia de la CPU (o viceversa). ← correcta
   - c) El espacio físico insuficiente dentro de la caja del ordenador para colocar un disipador grande.
   - d) La falta de espacio en la memoria caché L3 para abrir un navegador web.
   - *Explicación:* Ocurre cuando un componente desproporcionadamente inferior limita el rendimiento global del hardware más potente.
