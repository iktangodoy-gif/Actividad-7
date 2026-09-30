# Actividad-7

# Tipos de Datos en Bases de Datos

## 1.Investiga los tipos de datos más comunes en una base de datos, como INT, VARCHAR, DATE, DECIMAL, etc…
## 2.Da máximo 3 ejemplos de cada tipo de dato y explica brevemente cómo se utilizan en situaciones reales (por ejemplo, en el tipo de dato INT puedes almacenar; la edad, documento de identidad, cantidad o stock).

### INT
Se utiliza para almacenar números enteros, es decir, números que no tienen decimales. Por ejemplo: 10, 25, 100 o -5.

### VARCHAR
Se utiliza para almacenar texto o cadenas de caracteres. Permite guardar textos de diferentes longitudes, como nombres, ciudades o correos electrónicos. Por ejemplo: "Carlos" o "Colombia".

### CHAR
Se utiliza para almacenar texto de longitud fija. Es útil cuando todos los valores tienen una cantidad determinada de caracteres. Por ejemplo: "ABC123".

### TEXT
Se utiliza para almacenar textos largos, como descripciones, comentarios, observaciones o artículos.

### DATE
Se utiliza para almacenar fechas. Normalmente se escribe en el formato AAAA-MM-DD. Por ejemplo: 2026-09-30.

### TIME
Se utiliza para almacenar horas. Por ejemplo: 08:30:00.

### DATETIME
Se utiliza para almacenar una fecha y una hora al mismo tiempo. Por ejemplo: 2026-09-30 08:30:00.

### DECIMAL
Se utiliza para almacenar números con decimales de forma exacta. Es muy utilizado para precios, dinero y valores que necesitan precisión. Por ejemplo: 15000.50.

### FLOAT
Se utiliza para almacenar números con decimales aproximados. Puede utilizarse para cálculos científicos o valores que no necesitan una precisión exacta. Por ejemplo: 3.14159.

### BOOLEAN
Se utiliza para almacenar dos posibles valores: verdadero o falso. Por ejemplo: TRUE o FALSE. Puede utilizarse para indicar si un usuario está activo o inactivo.

### BIGINT
Se utiliza para almacenar números enteros muy grandes, cuando los valores pueden superar la capacidad de un INT. Por ejemplo: 9000000000.

### BLOB
Se utiliza para almacenar datos binarios, como imágenes, archivos u otros tipos de información que no se almacenan como texto normal.

## 3.Responde a la siguiente pregunta: 
"¿Qué piensas cuando escuchas la frase 'No hay sistema' y cómo crees que esto afectaría a las personas?" Menciona las consecuencias específicas de la ausencia de sistemas informáticos, como pérdida de datos, ineficiencia o errores en el procesamiento de información, etc. 

Supongo que se refiere a que hay momentos en los que el software de gestión o registro de datos de alguna tienda o empresa deja de funcionar y requiere un mantenimiento.

Ahora, las consecuencias en la caída de un sistema informático son variadas; primero, esto puede ocasionar que los archivos se pierdan o vuelvan corruptos debido a la interrupción abrupta del sistema, además puede llevar a que la informacion llegue inconsistente.
También genera que debido a que el sistema esta caído y no puede responder solicitudes, estas se acumulen y lo sobrecarguen, impidiendo que se reestablezca rapidamente.

## 4.Reflexiona sobre cómo la falta de sistemas informáticos puede impactar en sectores como la banca, la salud o el comercio. Y da máximo 3 ejemplos históricos donde haya ocurrido esto. 

Como dije anteriormente sin sistemas informáticos se generan muchos problemas con los datos, tanto los que entran y salen, como los que 

### 1. Sector Salud: El ciberataque *WannaCry* (2017)
En mayo de 2017, el ransomware *WannaCry* infectó miles de computadoras en todo el mundo, siendo el Servicio Nacional de Salud del Reino Unido (NHS) uno de los más afectados.

### 2. Sector Bancario: La falla masiva de *CrowdStrike* en la nube de Microsoft (2024)
En julio de 2024, una actualización defectuosa en un software de seguridad de la empresa CrowdStrike provocó la caída global de sistemas informáticos basados en Microsoft Windows.

### 3. Sector Bancario: La migración fallida del banco TSB (2018)
En abril de 2018, el banco británico TSB intentó migrar los datos de 5.2 millones de clientes desde la plataforma informática de su antiguo propietario hacia un nuevo sistema propio.

## Antes de las Computadoras: 5. Imagina cómo se realizaban las transacciones bancarias o solicitudes médicas antes de los sistemas informáticos. 

Antes de que existieran los sistemas informáticos, hacer un trámite en el banco o ir al médico era un proceso totalmente manual, basado en papel y mucha paciencia. En los bancos, los cajeros anotaban los depósitos y retiros a mano en libretas físicas, buscaban tu ficha entre miles de papeles organizados en archivadores de cartón y verificaban tu firma a simple vista, haciendo que cualquier movimiento o cobro de cheque tomara días. Por el lado de la salud, la historia clínica de cada persona era una carpeta física guardada en estantes gigantescos, las citas se agendaban anotando a lápiz en cuadernos de recepción y las recetas se escribían a mano en talonarios; si necesitabas ver a otro especialista, no había forma de compartir tu información a menos que alguien llevara la carpeta físicamente de un lugar a otro.

## 6. Elabora un cuadro comparativo que muestre las diferencias entre cómo se realizaban ciertos procesos antes de la existencia de la tecnología y cómo se llevan a cabo ahora. 

# Cuadro comparativo: Procesos antes y después de la tecnología

| Proceso | Antes de la tecnología | En la actualidad (Con sistemas informáticos) |
| :--- | :--- | :--- |
| **Transacciones bancarias** | Registros manuales en libretas físicas, ficheros de papel y filas en sucursales en horarios limitados. | Operaciones instantáneas desde aplicaciones móviles y banca en línea 24/7. |
| **Atención e historias clínicas** | Carpetas físicas guardadas en estantes gigantescos, difíciles de trasladar entre hospitales. | Historias clínicas digitales centralizadas, accesibles en segundos por autorizados. |
| **Agendamiento de citas** | Registro a lápiz en agendas de papel presencialmente o por llamadas telefónicas. | Reservas automatizadas a través de plataformas web, apps o bots de mensajería. |
| **Almacenamiento de información** | Archivos físicos de cartón, propensos a deterioro, incendios y pérdidas irreversibles. | Bases de datos en la nube con copias de seguridad automáticas y alta disponibilidad. |
| **Pagos y cobros** | Uso exclusivo de efectivo, cheques impresos o giros que tardaban días en hacerse efectivos. | Pagos digitales inmediatos mediante transferencias, tarjetas, códigos QR o billeteras móviles. |

## 12. Compara cómo se manejan los datos en Excel frente a una base de datos real. ¿Cuáles son las diferencias principales? Responde a la anterior pregunta. 
s
| Criterio | Excel / Hojas de Cálculo | Base de Datos (SQL) |
| :--- | :--- | :--- |
| **Capacidad** | Limitada (~1M de filas) | Prácticamente ilimitada (Terabytes) |
| **Integridad de datos** | Baja (permite mezcla de tipos y errores) | Alta (tipos estrictos y restricciones) |
| **Acceso simultáneo** | Limitado a pocos usuarios | Diseñado para miles de usuarios a la vez |
| **Relaciones** | Manuales (`XLOOKUP` / `BUSCARV`) | Nativas (Claves primarias y foráneas) |
| **Consultas** | Filtros visuales y Tablas dinámicas | Lenguaje SQL (consultas complejas) |
| **Seguridad** | Básica (protección por archivo/hoja) | Granular (permisos por usuario y tabla) |
