# Nombre del proyecto: BKI.

### Integrantes del equipo:
| Nombre                    | Número de control |
|---------------------------|---------------------------|
| Kevin Conejo Salazar      | 1222100714                |
| Brayan Yohani Morales Narváez | 1222100518            |
| Ivana Rocha Campos        | 1222100460                |


### Carta de liberación del proyecto:
![image](https://github.com/IvanaRocha/BKI/assets/135056237/1fbebe16-5561-4995-aa35-4f05f84b86f4)

### Lista del Hardware utilizado:

Aquí tienes la tabla corregida para que se vea correctamente:

| Id | Componente                | Descripción                                                                                   | Imagen | Cantidad | Costo total |
|----|---------------------------|-----------------------------------------------------------------------------------------------|--------|----------|-------------|
| 1  | Display LCD Pantalla 16x2 | Un display de cristal líquido (LCD) con capacidad para mostrar 16 caracteres en 2 líneas.   | ![Display Pantalla Oled 128x64](https://github.com/IvanaRocha/BKI/assets/146135319/8b52da40-e069-480d-8f4e-2a88906091d6) | 1        | $60         |
| 2  | Buzzer KY-006             | Un pequeño zumbador que puede generar sonidos simples.                                       | ![Buzzer KY-006](https://github.com/IvanaRocha/BKI/assets/146135319/faba01e3-3def-4461-b62d-2f311f203af4) | 1        | $40         |
| 3  | Placa ESP32               | Una placa de desarrollo basada en el microcontrolador ESP32, que ofrece capacidades de conectividad Wi-Fi y Bluetooth.| ![Placa ESP32](https://github.com/IvanaRocha/BKI/assets/146135319/89069f67-27e2-4fdc-9318-fc14d64adab4) | 1 | $280   |
| 4  | RFID-RC522                | Un módulo RFID que utiliza el chip RC522 para la lectura y escritura de tarjetas de proximidad.| ![RFID-RC522](https://github.com/IvanaRocha/BKI/assets/146135319/d5b05b70-3f76-42f2-bb6d-fd9429632624) | 1     | $60    |
| 5  | HC-SR04 Sensor Ultrasonico| El HC-SR04 es un sensor ultrasónico que consta de un transmisor y un receptor de ultrasonido.| ![HC-SR04 Sensor Ultrasonico](https://github.com/IvanaRocha/BKI/assets/146135319/a1fe9111-ead2-452f-b3d1-d51312f3f0f8) | 1  | $64    |
| 6  | Cable Dupont Multicolor Elegoo                 | Cable Dupont Multicolor Elegoo | ![Cable Dupont Multicolor Elegoo](https://github.com/IvanaRocha/BKI/assets/146135319/7d230318-3c68-41f1-b42d-70678812df70) | 1      | $70       |







### Lista de Software utilizado:

| ID | Software  | Versión | Tipo                                                                               |
|----|-----------|---------|------------------------------------------------------------------------------------|
| 1  | Fritzing  | 1.0.2   | Software de diseño electrónico / CAD (Computer-Aided Design).                      |
| 2  | Grafana   | 10.4.2  | Plataforma de visualización y monitoreo de datos.                                   |
| 3  | Node-RED  | 2.0     | Entorno de desarrollo para el Internet de las Cosas (IoT) y la integración de sistemas.|
| 4  | Thonny    | 4.1.4   | Entorno de desarrollo integrado (IDE) para Python.                                   |
| 5  | GitHub    | 3.12    | Plataforma de desarrollo colaborativo para alojar proyectos utilizando el control de versiones de Git. |
| 6  | Tinkercad | 14.1.2 | Plataforma en línea para el diseño y simulación de circuitos electrónicos y modelos 3D. |
| 7  | PostgreSQL| PostgreSQL13 | Sistema de gestión de bases de datos relacional (RDBMS, por sus siglas en inglés). |

### Visión del producto:

Público:
La tienda de OutfitGC se enfoca en brindar una experiencia innovadora y conveniente a la empresaria Georgina, quien busca adquirir calzado de moda de manera eficiente.

Problema:
Georgina enfrenta una carga de trabajo manual y consume mucho tiempo al registrar la información de cada par de zapatos individualmente en una hoja de cálculo.

Solución:
Implementar un sistema de escaneo de códigos de barras o etiquetas RFID para los zapatos que llegan a su tienda. Este sistema automatizado podría leer la información de cada par de zapatos y registrarla automáticamente en una base de datos relacional sql.

### Conexiones:

#### Modelo de Tinkercad
![image](https://github.com/IvanaRocha/BKI/assets/135056237/285c54b2-170b-4b01-9d71-ac164f64ce28)

#### Circuito de fritzing



#### Circuito armado
![image](https://github.com/IvanaRocha/BKI/assets/135056237/61d72912-ea35-44bc-b6f0-e9cd5ccdc860)




### Funcionalidades:

| ID | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  | Implementación de hoja de Excel para seguimiento de inventario | Alta | 12 horas | Verificar que las etiquetas de ciertos productos sean detectadas y guardadas correctamente en una base de datos. Luego, confirmar que los datos se reflejen adecuadamente en una hoja de Excel para monitoreo de inventarios. | Kevin |
| 2  | Creación de gráficas en Grafana para visualización de registros de zapatos | Alta | 4 horas | Generar gráficas que muestren de forma intuitiva y comprensible las estimaciones de registros de zapatos. | Brayan |
| 3  | Desarrollo del CRUD para gestión de datos | Alta | 10 horas | Verificar que todas las funcionalidades del CRUD (actualización, eliminación e inserción) operen correctamente. | Kevin |
| 4  | Implementación de sistema de escaneo de códigos de barras o etiquetas RFID para registro automatizado de zapatos | Alta | 7 horas | Probar el sistema de escaneo para asegurar que lee correctamente la información de cada par de zapatos y la registra automáticamente en la base de datos relacional SQL. | Kevin y Brayan |
| 5  | Desarrollo de interfaz de usuario para el sistema de escaneo de códigos de barras o etiquetas RFID | Alta | 4 horas | Verificar que la interfaz de usuario sea intuitiva y fácil de usar para Georgina. | Brayan y Kevin |
| 6  | Implementación de display OLED para mostrar información relevante del inventario | Media | 2 horas | Verificar que el display OLED muestre de forma clara y legible información actualizada del inventario. | Brayan |
| 7  | Integración de sensor de proximidad para detectar movimiento en el local | Alta | 4 horas | Verificar que el sensor de proximidad detecte de manera precisa el movimiento en el almacén y registre los eventos correctamente en el sistema de gestión de inventario. | Ivana |




### Prototipo dibujo:
| Concepto | Prototipo |
|----------|-----------|
| Uso      | ![WhatsApp Image 2024-02-12 at 9 14 12 PM](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/0e9b5acc-e60c-47f5-97bc-aee0f3a0d0a8.png) |
| Aparato  | ![WhatsApp Image 2024-02-12 at 9 32 07 PM](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/1ca3decb-5d76-49ba-8366-4e07bc8e1905.png) |


### Evidencias de Funcionamiento
#### Flujos de Node RED
##### CRUD
![image](https://github.com/IvanaRocha/BKI/assets/135056237/9c28746a-c2bc-4a13-b988-2b4e0fdceec7)
[CRUD](BKI/Codigos/CRUD)



##### Registro
![image](https://github.com/IvanaRocha/BKI/assets/135056237/0affd358-313f-4433-9b31-fd0081936aae)




