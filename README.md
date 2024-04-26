Nombre del proyecto: BKI.

### Integrantes del equipo:
| Nombre                    | Número de control |
|---------------------------|---------------------------|
| Ivana Rocha Campos        | 1222100460                |
| Kevin Conejo Salazar      | 1222100714                |
| Brayan Yohani Morales Narváez | 1222100518            |

### Carta de liberación del proyecto:
![image](https://github.com/IvanaRocha/BKI/assets/135056237/1fbebe16-5561-4995-aa35-4f05f84b86f4)

### Lista del Hardware utilizado:

| Id | Componente                | Descripción                                                                                   | Imagen | Cantidad | Costo total |
|----|---------------------------|-----------------------------------------------------------------------------------------------|--------|----------|-------------|
| 1  | Display LCD Pantalla 16x2 | Un display de cristal líquido (LCD) con capacidad para mostrar 16 caracteres en 2 líneas.   | ![Display Pantalla Oled 128x64](![image](https://github.com/IvanaRocha/BKI/assets/146135319/8b52da40-e069-480d-8f4e-2a88906091d6)
) | 1        | $60         |
| 2  | Buzzer KY-006             | Un pequeño zumbador que puede generar sonidos simples.                                       | ![Buzzer KY-006](https://github.com/IvanaRocha/BKI/assets/146135319/faba01e3-3def-4461-b62d-2f311f203af4) | 1        | $40     |
| 3  | Placa ESP32               | Una placa de desarrollo basada en el microcontrolador ESP32, que ofrece capacidades de conectividad Wi-Fi y Bluetooth.| ![Placa ESP32](https://github.com/IvanaRocha/BKI/assets/146135319/89069f67-27e2-4fdc-9318-fc14d64adab4) | 1 | $280   |
| 4  | RFID-RC522                | Un módulo RFID que utiliza el chip RC522 para la lectura y escritura de tarjetas de proximidad.| ![RFID-RC522](https://github.com/IvanaRocha/BKI/assets/146135319/d5b05b70-3f76-42f2-bb6d-fd9429632624) | 1     | $60    |
| 5  | HC-SR04 Sensor Ultrasonico| El HC-SR04 es un sensor ultrasónico que consta de un transmisor y un receptor de ultrasonido.| ![HC-SR04 Sensor Ultrasonico](https://github.com/IvanaRocha/BKI/assets/146135319/a1fe9111-ead2-452f-b3d1-d51312f3f0f8) | 1  | $64    |
| 6  | Cable Dupont Multicolor Elegoo                 | Cable Dupont Multicolor Elegoo | ![Cable Dupont Multicolor Elegoo ](![Uploading image.png…]()
) | 1      | $0 ya los teniamos        |




### Lista de Software utilizado:

| ID | Software  | Versión | Tipo                                                                               |
|----|-----------|---------|------------------------------------------------------------------------------------|
| 1  | Fritzing  | 1.0.2   | Software de diseño electrónico / CAD (Computer-Aided Design).                      |
| 2  | Grafana   | 10.4.2  | Plataforma de visualización y monitoreo de datos.                                   |
| 3  | Node-RED  | 2.0     | Entorno de desarrollo para el Internet de las Cosas (IoT) y la integración de sistemas.|
| 4  | Thonny    | 4.1.4   | Entorno de desarrollo integrado (IDE) para Python.                                   |
| 5  | GitHub    | 3.12    | Plataforma de desarrollo colaborativo para alojar proyectos utilizando el control de versiones de Git. |
| 6  | Tinkercad, SketchUp | 14.1.2 | Plataforma en línea para el diseño y simulación de circuitos electrónicos y modelos 3D. |
| 7  | PostgreSQL| PostgreSQL13 | Sistema de gestión de bases de datos relacional (RDBMS, por sus siglas en inglés). |

### Visión del producto:

Público:
La tienda de Aufit Geser se enfoca en brindar una experiencia innovadora y conveniente a la empresaria Georgina, quien busca adquirir calzado de moda de manera eficiente.

Problema:
Georgina enfrenta una carga de trabajo manual y consume mucho tiempo al registrar la información de cada par de zapatos individualmente en una hoja de cálculo.

Solución:
Implementar un sistema de escaneo de códigos de barras o etiquetas RFID para los zapatos que llegan a su tienda. Este sistema automatizado podría leer la información de cada par de zapatos y registrarla automáticamente en una base de datos relacional sql.

### Conexiones:
![Fritzing](https://github.com/IvanaRocha/BKI/assets/146135319/bc273774-4dc5-461d-9442-bbf3920ef13f)
![Circuito 2](https://github.com/IvanaRocha/BKI/assets/146135319/73868d91-f22f-4255-8a65-43b9571fffea)
![Grafica_Grafama](https://github.com/IvanaRocha/BKI/assets/146135319/c2b30620-b588-4a46-8fb4-2027079dbfbb)


### Funcionalidades:

| ID | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  | Implementación del RFID | Alta | 12 horas | Se ingresan etiquetas a ciertos productos y la configuración lo detecta y lo guarda en una base de datos para ser monitoreado mediante una inserción de inventarios. | Kevin, Brayan e Ivana |
| 2  | Sensor que detecta el movimiento | Alta | 2 horas | Cada vez que alguien entra, el sensor lo detecta y el usuario puede ver que alguien entró a su tienda. | Kevin, Brayan e Ivana |

### Prototipo dibujo:
| Concepto | Prototipo |
|----------|-----------|
| Uso      | ![WhatsApp Image 2024-02-12 at 9 14 12 PM](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/0e9b5acc-e60c-47f5-97bc-aee0f3a0d0a8.png) |
| Aparato  | ![WhatsApp Image 2024-02-12 at 9 32 07 PM](https://github.com/BrayanYNm67/EquipoKBI/assets/135056237/1ca3decb-5d76-49ba-8366-4e07bc8e1905.png) |
