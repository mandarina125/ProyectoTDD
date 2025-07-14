- Estructura del proyecto
src/ → Código Java principal

test/ → Clases de pruebas unitarias

lib/ → Librerías externas (.jar de JUnit, Mockito, MySQL, etc.)

sql/ → Script base.sql con tabla y datos iniciales

run_tests.bat → Script para compilar y ejecutar las pruebas

- Tecnologías utilizadas
Java 17+

JUnit 4.13.2

Mockito 4.x

MySQL Connector/J 8.x

ByteBuddy / Objenesis (para Mockito)

db4free.net como base de datos SQL gratuita

Git y GitHub para control de versiones

- Cómo ejecutar el proyecto
Instala Java y Git en tu sistema.

Descarga los .jar necesarios desde Maven Central:

junit-4.13.2.jar

hamcrest-core-1.3.jar

mockito-core-4.0.0.jar

mysql-connector-java-8.4.0.jar

byte-buddy-1.10.22.jar

objenesis-3.2.jar

Coloca todos los archivos .jar dentro de la carpeta lib/

- Ciclo TDD aplicado
✔ Pruebas RED implementadas y versionadas con Git
✔ Commit GREEN posterior
✔ Refactor aplicado según el patrón TDD
✔ Evidencia de pruebas en consola y cobertura mínima cumplida

🚀 Autor
Marielen Muñoz
