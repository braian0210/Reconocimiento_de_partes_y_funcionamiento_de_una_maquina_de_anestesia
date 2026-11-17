# Reconocimiento_de_partes_y_funcionamiento_de_una_maquina_de_anestesia

# Introducción

Una máquina de anestesia es el equipo que mantiene al paciente dormido y estable durante una cirugía. Le entrega oxígeno, le ayuda a respirar y mezcla los gases anestésicos en las dosis que se necesitan (1), (2). La dosis es lo delicado: si la máquina entrega demasiado anestésico puede causar daño cerebral o un paro cardíaco, y si entrega muy poco el paciente puede despertarse en plena operación.

Los equipos modernos redujeron la probabilidad de que esto pase, y las fallas que todavía ocurren suelen estar relacionadas con quien la usa (3). Además, por dentro la máquina es más sencilla de lo que parece: es un conjunto de tuberías y sistemas de bombeo que entregan una mezcla de gases de forma controlada (4).

En esta práctica conocimos la máquina de anestesia WATO EX-20 de Mindray que tiene el laboratorio de la universidad (Fig. 1 y Fig. 2). La práctica fue demostrativa y la máquina no estaba en funcionamiento, así que nos dedicamos a reconocer sus partes y a revisar el manual del operador y la lista de verificación que trae pegada. Conocer cada subsistema nos ayuda a entender para qué sirve cada pieza, y por qué importan su mantenimiento y sus alarmas.

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 13 01 PM" src="https://github.com/user-attachments/assets/85a96ceb-6402-4f5c-a9d6-d82fcd0c3420" />

Fig1. vista de frente: se ve el letrero WATO EX-20, los flujómetros, las perillas de gases y la pantalla

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 13 10 PM" src="https://github.com/user-attachments/assets/9bbdde5e-4a2d-43d9-99b2-52fa82b8a366" />

Fig2. vista lateral con el sistema de respiración, la bolsa verde, el recipiente del absorbente y el carro con cajones



# Objetivos

Objetivo General

• Familiarizar al estudiante con los componentes,
funcionamiento y labores de mantenimiento de una máquina de anestesia.

Objetivos Específicos

• Identificar las partes principales de una máquina de anestesia WATO EX20.

• Comprender el funcionamiento y modos de operación de una máquina de
anestesia.

• Reconocer la relevancia de las labores de mantenimiento aplicadas a una
máquina de anestesia.

# Metodología

PARTE A

1. A continuación, responda las siguientes preguntas tras haber realizado una
revisión de la literatura relacionada. Se sugiere buscar en Internet el manual de
operación o “service manual” de la máquina de anestesia WATO EX-20 y tener
una copia impresa. En caso de utilizar modelos de IA generativa (e.g.,
ChatGPT) debe verificar la información contra una fuente confiable (e.g., libros,
manuales, informes técnicos).


a. ¿Cuántos y cuáles son los tipos de anestesia que comúnmente se aplican
durante una cirugía? Explique cada uno.

Son cuatro: anestesia general, sedación, anestesia regional y anestesia local (5). Cambian en qué tan grande es la zona que se adormece y en si el paciente sigue consciente.

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 26 18 PM" src="https://github.com/user-attachments/assets/726dbbf4-0c54-4c36-9805-a9d01a284d7e" />

Fig. 3. Portada del manual del operador de la WATO EX-20.

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 13 26 PM" src="https://github.com/user-attachments/assets/8a229357-2fa4-4edb-b134-392358aa3bea" />

Fig. 4. Lista de verificación preoperatoria pegada a la máquina.



La general afecta todo el cuerpo y deja al paciente inconsciente y sin movimiento. Se usa en cirugías largas o de órganos internos, como una cirugía de espalda, y se da por la vena o como un gas que se inhala (5). Es la que más depende de la máquina de anestesia, porque la máquina incorpora un ventilador para entregar bien los anestésicos inhalados (6).

En la sedación el paciente se relaja y puede dormirse, pero sigue consciente y, según qué tanto se le sede, hasta puede hablar. Se da por la vena y se usa, por ejemplo, en colonoscopias o en trabajos dentales complejos (5).

La regional adormece una zona más grande, como un brazo, una pierna o todo lo que queda por debajo de la cintura. Se usa en cirugías de mano y de articulaciones, en cesáreas y para el dolor del parto. El paciente queda despierto y cómodo, y el anestésico se aplica con una inyección o un catéter (5).

La local adormece una zona pequeña, como un diente o un pedazo de piel que se va a suturar. El paciente está despierto y el anestésico se aplica con inyección, loción o spray, gotas para los ojos o parche (5).

b. ¿Con cuáles gases trabaja una máquina de anestesia y qué función
cumple cada uno? ¿Cuáles de ellos se incorporan a la máquina mediante
sistema de alta presión?

La máquina recibe tres gases, oxígeno (O₂), óxido nitroso (N₂O) y aire, y con ellos arma la mezcla que respira el paciente (6), (7). A esa mezcla se le suma el vapor del anestésico líquido, que se produce en el vaporizador (7).

El oxígeno es el que mantiene oxigenado al paciente, una de las funciones principales de la máquina (6). Por seguridad va de último en los flujómetros, para que una fuga de los otros gases no deje una mezcla con poco oxígeno (7). Además, el botón de flujo rápido manda oxígeno puro de golpe al sistema de respiración cuando se necesita (7), (8).

El óxido nitroso es un gas anestésico que se mezcla con el oxígeno. Como con este gas han ocurrido mezclas con poco oxígeno, la máquina amarra su flujo al del oxígeno, y si la presión de oxígeno baja, un dispositivo de seguridad reduce o corta el óxido nitroso (6), (7).

El aire se mezcla con el oxígeno para bajar su concentración cuando no hace falta oxígeno puro, y en esta máquina el ventilador se puede mover con oxígeno o con aire (9).

El vaporizador convierte el anestésico líquido en un vapor con la concentración que se programa. Cada vaporizador es para un solo anestésico, y los seguros de la máquina no dejan que funcione más de uno al tiempo (6), (7).

Por el sistema de alta presión entran los gases que vienen en cilindros: oxígeno, óxido nitroso y aire. Son cilindros pequeños, tipo E, que van en la parte de atrás de la máquina y guardan los gases a presiones muy altas: entre 2000 y 2200 psi el oxígeno, cerca de 1800 psi el aire y 745 psi el óxido nitroso (6), (7). Un regulador baja esa presión a unos 45 psi antes de usarlos (7), y los cilindros sirven sobre todo de respaldo cuando falla la tubería del hospital (6).

Los gases que llegan por la tubería no son de alta presión: vienen a 45–60 psi y entran al sistema de presión intermedia (7). En esta máquina las entradas de tubería están marcadas N₂O, O₂ y AIR, con un rango de 280 a 600 kPa (8). Atrás tiene mangueras de tres colores, con los mismos colores de las perillas del panel (Fig. 5 y Fig. 6), y el único manómetro de cilindro instalado en el panel de adelante es el del oxígeno (Fig. 5).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 16 07 PM" src="https://github.com/user-attachments/assets/8fb58f65-f2fe-4679-9a62-97057facf4a9" />

Fig. 5. Panel de gases: perillas, manómetros de tubería y manómetro del cilindro de O₂.

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 20 27 PM" src="https://github.com/user-attachments/assets/c1c8d87e-90e4-4ef7-80b6-37042e1bfee4" />

Fig. 6. Mangueras de gases en la parte trasera.



c. ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su
función? ¿Qué partes de este sistema podrían esterilizarse por medio de
autoclave?

El sistema de respiración es el recorrido por donde viajan los gases entre la máquina y el paciente. Lleva hacia él la mezcla de oxígeno y anestésico, recoge lo que exhala y le quita el CO₂ para poder volver a usar ese gas (6). El tipo más usado es el sistema circular (6).

El manual enumera, entre otras piezas, los conectores de inspiración y de espiración, las válvulas de retención de cada sentido, el indicador de presión de las vías respiratorias, el alojamiento del fuelle, el brazo de la bolsa, el interruptor de ventilación por bolsa o mecánica, la válvula APL, el botón de flujo rápido de O₂, el interruptor ACGO y el recipiente absorbente de CO₂ (8) (Fig. 7 y Fig. 8). En la máquina del laboratorio se ve armado, con sus mangueras, la bolsa y el recipiente absorbente, en la Fig. 9.

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 23 05 PM" src="https://github.com/user-attachments/assets/8aab6700-8589-4b6d-ba2d-65c6cc63e597" />

Fig. 7. Sistema de respiración según el manual (página 2-5).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 23 38 PM" src="https://github.com/user-attachments/assets/62f5c89b-cf7a-40ff-84d9-a70d98fa8d4b" />

Fig. 8. Lista de partes del sistema de respiración (página 2-6).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 19 26 PM" src="https://github.com/user-attachments/assets/5776e069-c6f2-46b2-a1c2-9e8474762ffc" />

Fig. 9. Sistema de respiración armado en la máquina del laboratorio.


Las válvulas de retención dejan pasar el gas en un solo sentido (6). El recipiente absorbente le quita el CO₂ al gas exhalado y así se puede reutilizar (6), (8). El interruptor sirve para escoger si se ventila a mano con la bolsa o con el ventilador, y la válvula APL fija el límite de presión del sistema durante la ventilación manual (8). El interruptor ACGO detiene la ventilación mecánica y manda el gas fresco a un sistema de respiración externo (8).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 14 33 PM" src="https://github.com/user-attachments/assets/09a9657f-9b4f-4090-8044-9a6a40ca7499" />

Fig. 10. Módulo del sistema de respiración, con la válvula APL .

d. ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste
cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

Según la ficha técnica de la EX-20, el ventilador trabaja con cuatro modos de ventilación: manual, ventilación por control de volumen (VCV), ventilación por control de presión (PCV) y ventilación mandatoria intermitente sincronizada (SIMV) (11). En la pantalla, cada modo mecánico tiene su propia pestaña con los parámetros que se pueden ajustar, y se aplica con el botón Set Mode. El modo manual se prepara con el interruptor Auto/Manual y la válvula APL (10).

El manual de la EX-35Vet también describe un modo de presión de soporte (PS) que la ficha de la EX-20 no menciona (10), (11). Por eso contamos cuatro submenús de ventilación para la EX-20. La tecla de menú abre otra ventana con cinco pestañas: General, Pantalla, Historial, Sistema y Servicio. Sirven para calibrar sensores, ajustar la pantalla, ver tendencias y configurar el equipo (10), y por eso los submenús del ventilador son los modos.

La pausa inspiratoria (Tpause) se activa en el modo VCV, y en el manual de la serie también en SIMV por volumen (10). Es el porcentaje del tiempo de inspiración en que el gas se mantiene retenido en el pulmón, y sirve para que se reparta mejor (10). Se puede dejar apagada (OFF) o poner entre 5 y 60 % del tiempo de inspiración, en pasos de 5 % (10), (11). De fábrica viene apagada en VCV (10). Para activarla se selecciona la tecla Tpause en la parte de abajo de la pantalla, se presiona y gira la perilla de control hasta el valor y se presiona otra vez para confirmar. Después se confirma el modo con Set Mode (10). En el modo de presión no aparece entre los parámetros (10).


PARTE B

1. Identifique y ubique las siguientes partes de la máquina de anestesia WATO
EX-20, explicando su función.

<img width="1600" height="900" alt="WhatsApp Image 2026-11-10 at 2 20 10 PM" src="https://github.com/user-attachments/assets/c722ef50-e0b5-48ce-a12b-be05eb365bd7" />

Fig. 11. Placa de datos de la máquina, en el panel trasero.

a. Vaporizador

El vaporizador se monta en el colector, que tiene dos posiciones para vaporizador (9). Cuando tomamos la foto no había ninguno montado, y solo se ven las conexiones metálicas del colector y sus dos perillas blancas (Fig. 12).

<img width="1600" height="900" alt="WhatsApp Image 2026-11-10 at 2 22 02 PM" src="https://github.com/user-attachments/assets/afeb5eed-8ba9-4fa7-b61c-8d286a69ba9f" />

Fig. 12. Colector de la máquina, sin vaporizador montado.

Su función es convertir el anestésico líquido en un vapor con una concentración calibrada (7). Los de derivación variable usan un dial que reparte el gas fresco que pasa por la cámara del anestésico, compensan los cambios de temperatura y sirven para un solo agente (6). Además, unos seguros impiden usar más de un vaporizador al mismo tiempo (6).

En el manual impreso, el vaporizador se monta sobre el colector con la palanca de bloqueo, los tornillos de interbloqueo y el eje de bloqueo (8) (Fig. 13). Para llenarlo con el sistema Pour Fill, el control de concentración debe estar en 0 y el tornillo de drenaje bien apretado. Luego se llena despacio y se para al llegar a la marca de nivel máximo (8) (Fig. 14).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 22 38 PM" src="https://github.com/user-attachments/assets/ab138052-f5ec-4240-adaa-ad6908f30b57" />

Fig. 13. Montaje del vaporizador en el colector (manual, p. 9-19).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 22 26 PM" src="https://github.com/user-attachments/assets/fba8b628-7554-4ee4-9c8b-a3d4600f86ff" />

Fig. 14. Llenado del vaporizador con el sistema Pour Fill (manual, p. 9-23).


b. Válvula APL

La válvula APL está en el módulo del sistema de respiración, abajo a la derecha. Es la perilla grande con una escala en cmH₂O que llega hasta 75 (Fig. 10).

Funciona como una válvula de alivio que evita presiones demasiado altas en el circuito, que podrían causar barotrauma (6). En modo manual, deja salir el exceso de gas hacia el sistema de evacuación durante la espiración, y se ajusta entre 1 y 75 cmH₂O (10). Se deja abierta en respiración espontánea y parcialmente cerrada para ventilar a mano con la bolsa (6).

c. Recipiente absorbente de CO2

El recipiente absorbente está debajo del módulo del sistema de respiración. Es el recipiente transparente con la marca MAX y el símbolo de 134 °C, y en la foto está sin absorbente (Fig. 15).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 15 25 PM" src="https://github.com/user-attachments/assets/4f70df26-9769-4c6c-9ee3-782b28e9408d" />

Fig. 15. Recipiente absorbente de CO₂, sin absorbente.

Quita el CO₂ del gas que exhala el paciente para poder reutilizar el gas fresco, lo que permite trabajar con flujos bajos (7). El absorbente tiene bases, como hidróxidos de calcio y sodio, que atrapan el CO₂ (6).

d. Fuelle

El fuelle está dentro del alojamiento transparente que se ve arriba del módulo del sistema de respiración, con una escala de volumen marcada en el costado (Fig. 16).

<img width="900" height="1600" alt="WhatsApp Image 2026-11-10 at 2 17 37 PM" src="https://github.com/user-attachments/assets/52dd9361-a1b8-4fb3-9dac-a153498cf9e9" />

Fig. 16. Alojamiento del fuelle sobre el módulo del sistema de respiración.

Durante la inspiración, el gas impulsor comprime el fuelle y empuja el gas hacia los pulmones. Durante la espiración, el gas que exhala el paciente lo vuelve a llenar (10). Ese gas impulsor sale del suministro de O₂ o de aire y actúa por fuera del fuelle (10).

2. Si el ventilador muestra el mensaje “batería en uso” y el paciente se encuentra
conectado a la máquina ¿Qué acción debería ejecutarse?

es una alarma de prioridad baja que se activa cuando falla la energía de la red (10). En la prueba de falla de energía del manual, al desconectar la red el sistema muestra este mensaje, y al reconectarla se enciende el indicador de red y el mensaje desaparece (12). La tabla de alarmas del manual solo da la causa y no una acción (10), así que esta respuesta combina el manual con la literatura. Con el paciente conectado haríamos lo siguiente:

Seguir ventilando y vigilar al paciente, sin desconectarlo. La máquina sigue funcionando con su batería.
Revisar los indicadores de red y de batería, confirmar que el cable esté conectado a un tomacorriente con energía (13) y pasarlo a otro tomacorriente si hace falta.
Tener en cuenta la autonomía. El manual de la serie da unos 90 minutos con una batería y 240 con dos, con baterías nuevas y cargadas (10), y el folleto de la EX-30/20 incluye una batería de litio de 90 minutos (14).
Avisar al equipo quirúrgico y al técnico.
Si la energía no vuelve y aparece “Low Battery Voltage!” se vuelve prioridad alta (10), preparar la ventilación manual. El manual indica que el sistema se apaga al menos 5 minutos después de la primera alarma de batería baja (10). Debe haber una bolsa autoinflable en cada lugar de anestesia, revisada antes de cada caso (13), y se recomienda para ventilar temporalmente si la máquina falla (6).

3. ¿Con qué frecuencia debería reemplazarse el recipiente absorbente de CO2?

El manual no da un intervalo fijo. Dice que el absorbente se cambia cuando haga falta, que se use el monitoreo de CO₂ para decidirlo y que el cambio de color solo es un indicador aproximado (10). La literatura da las mismas señales. El color cambia a medida que el absorbente se satura y se recomienda cambiarlo cuando está más o menos a dos tercios de saturación (6). También se cambia cuando el monitor detecta CO₂ en la rama inspiratoria (6), (15).

Hay dos cuidados al cambiarlo. Si el absorbente se seca por completo puede soltar monóxido de carbono al contacto con los anestésicos, y cambiarlo durante la ventilación puede causar fugas en equipos sin función BYPASS (10). Por eso conviene esperar al final del caso, si es posible (15).

4. ¿Cuál es el procedimiento para verificar si hay fuga en el cilindro de alta
presión?

1) Encender el sistema y desconectar la tubería de O₂ (10).
2) Cerrar el flujómetro de O₂ y abrir despacio la válvula del cilindro (10).
3) Anotar la presión del cilindro y cerrar la válvula (10).
4) Volver a anotar la presión después de un minuto (10).
5) Si la presión baja más de 5000 kPa (725 psi), hay fuga. Se cambia el empaque del cilindro y se repite la prueba, y si la fuga sigue no se usa el suministro por cilindro (10).

Para el N₂O se repite con la tubería de N₂O desconectada y el límite baja a 700 kPa (100 psi) en un minuto. Para el aire se sigue el mismo procedimiento del oxígeno (10). Antes de la prueba se abre cada válvula despacio y se confirma que hay presión suficiente (10). El manual la programa cada día antes del primer uso y después de cualquier mantenimiento (10).

5. ¿Influye el contar o no con el sensor de O2 al hacer la prueba sobre el sistema
de control de flujo? ¿De qué forma?

Sí influye, porque el manual describe la prueba de dos formas según haya o no monitoreo de O₂ (10), (12).

Sin sensor, la prueba usa solo los flujómetros. Se comparan las lecturas con una tabla de pares de flujos de N₂O y O₂, subiendo y bajando el flujo, y no se usa ninguna lectura del sensor (10). Además se desconecta el suministro de O₂ y se confirma que suenan las alarmas de falla de suministro de O₂ y de presión baja del gas impulsor (12). El manual advierte que tener suficiente O₂ en el gas fresco puede no evitar mezclas con poco oxígeno en el sistema de respiración (12), porque sin sensor no hay una lectura real de la mezcla.

Con sensor, el sensor debe estar bien calibrado y antes se hace la prueba de monitoreo de O₂ y sus alarmas. Luego la concentración medida debe ser de al menos 25 % en todo el rango, subiendo y bajando el flujo (10). Esa prueba del sensor no se exige si la máquina no tiene sensor configurado (10). Mindray incluye el sensor de O₂ en la configuración completa de la EX-20 (9), así que en nuestra máquina corresponde la prueba con monitoreo, si el sensor está instalado.

6. ¿Para qué se requiere el sistema de presión negativa?

El dispositivo de succión por presión negativa sirve para aspirar los líquidos de la faringe y el vómito del paciente (10), lo que ayuda a mantener despejada la vía respiratoria. Recoge ese líquido en un frasco con protección contra desbordamiento (10). El vacío lo genera un venturi que usa aire de la misma máquina, con al menos 50 kPa de vacío cuando el gas llega a 280 kPa (10).

PARTE C

• Pregunta 1: ¿Qué tipos de anestésicos son los más usados en cirugía?

Entre los inhalados, los más usados son el óxido nitroso, el isoflurano, el sevoflurano y el desflurano, y la fuente todavía lista también el halotano (18). Todos producen amnesia e inmovilidad, y el óxido nitroso además calma el dolor. Los líquidos volátiles necesitan vaporizador, mientras que el óxido nitroso ya es un gas (18). Estos agentes se suelen combinar con anestésicos por la vena (18). Por la vena hay otros grupos: la literatura habla de cinco clases de fármacos en anestesia general, que son los anestésicos intravenosos, los inhalados, los sedantes intravenosos, los opioides sintéticos y los relajantes musculares (19). La forma más común de lograr una anestesia general es empezar con medicamentos por la vena y mantener con un anestésico volátil (19). El propofol es un buen ejemplo del lado intravenoso, porque se usa para inducir la anestesia, para mantenerla y para sedar al paciente (20). Aparte están los anestésicos locales, que bloquean los nervios en la piel, en nervios periféricos o en el espacio de la columna, y su efecto dura desde 30 minutos hasta 12 horas o más según el sitio y el fármaco. Entre los más conocidos están la lidocaína, la bupivacaína y la ropivacaína (21). La elección final depende del paciente y del procedimiento (22). Las fuentes que revisamos listan los fármacos más usados, pero no dan porcentajes de uso, así que no podemos ordenarlos con cifras.

• Pregunta 2: ¿Qué diferencias plantea el modelo EX-35 con respecto al EX20?

Las dos máquinas se parecen en su estructura: pesan menos de 120 kg, miden 1375 mm de alto, 880 mm de ancho con el circuito montado y 620 mm de fondo, y tienen dos posiciones de vaporizador (11)(23). Las diferencias están en la ventilación, el monitoreo, la pantalla y la batería, ademas, que el volumen mínimo más bajo y los modos adicionales amplían los pacientes y las situaciones que la máquina puede atender, y el módulo de gases permite vigilar la concentración del anestésico durante la cirugía (23)(24). Para cerrar la comparación con datos propios haría falta pedir la hoja técnica vigente al distribuidor de la unidad, L.A.S Electromedicina, que aparece en la placa de datos (Fig. 11).


# Análisis y Discusión de Resultados

Análisis 1: Revise sobre las fallas que pueden presentarse en el
funcionamiento de alguno de los subsistemas que componen la máquina de
anestesia, así como lo que las produce.

Como la máquina estaba apagada, revisamos qué fallas puede avisar según el anexo D del manual del EX-35Vet (10), que es de la misma familia del EX-20. En el ventilador y el circuito respiratorio están las fallas más serias: presión de vía aérea alta o negativa, apnea y FiO2 baja, además de fugas, recipiente del absorbente sin asegurar, circuito sin montar, sensores de flujo fuera de rango y sensor de oxígeno sin calibrar. En la parte eléctrica las causas son un corte de luz que pasa la máquina a la batería y un voltaje de batería bajo, y en la CPU un ventilador de enfriamiento lento (10). Casi todas estas causas son de montaje, suministro o desgaste, y la literatura coincide en que pesa más el manejo del usuario que el daño del equipo (3)(6). Por eso la lista de verificación antes de usar la máquina ayuda a evitarlas (Fig. 4) (6). Falta confirmar estos mensajes en el manual impreso del EX-20 y, si el docente lo autoriza, revisar el historial de alarmas de la máquina encendida.

• Análisis 2: Ordene cada subsistema de la máquina en función del número
de fallas asociadas a este (de mayor a menor,) de acuerdo con la
información suministrada por el manual de operación.


# Conclusión 

Según lo que revisamos, las fallas más comunes al operar una máquina de anestesia tienen cuatro causas probables. La primera son las fugas y el montaje del circuito: un recipiente de absorbente sin asegurar, un circuito sin montar, una rama desconectada o un vaporizador mal cerrado (6)(10). La segunda es el suministro y la medición de gas, es decir, un cilindro o una línea de oxígeno que falla, baja presión del gas que mueve el fuelle, sensores de flujo fuera de rango y un sensor de oxígeno sin calibrar (10). La tercera es el desgaste de lo que se consume, como el absorbente de CO2 agotado, que deja pasar CO2 al paciente (6)(15). La cuarta es la energía, porque un corte de luz pasa la máquina a una batería de 90 minutos (14) y su voltaje bajo genera una alarma alta (10). Detrás de casi todas hay un factor humano (3)(6).

Como la mayoría de estas causas se pueden detectar antes de empezar, la lista de verificación preoperatoria (Fig. 4) y el montaje cuidadoso de las piezas reducen el riesgo de que una falla llegue al paciente (6). El siguiente paso es encender la máquina con apoyo del docente, repetir las pruebas de fuga y de flujo, y revisar su historial de alarmas para compararlo con el manual impreso del EX-20, claro esta, que los metodos utilizados son deductivos con base en lo observado en la lectura del manual, lo cual es informacion basada en como la maquina funciona perfectamente y como las investigaciones encuentran errores y sus patrones por lo cual no hay seguridad de informacion experimentada, sino unicamente de informacion recopilada. 

# Referencias 
