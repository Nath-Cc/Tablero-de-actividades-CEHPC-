# Caso Práctico de Ethical Hacking
## Aurora Market

---

## 1. Presentación del caso

**Aurora Market** es una plataforma de comercio electrónico que cuenta con una aplicación web utilizada por distintos tipos de usuarios.

La organización solicita una **evaluación de seguridad** de su aplicación web con el objetivo de identificar posibles vulnerabilidades, comprender los riesgos asociados y obtener recomendaciones que permitan fortalecer la seguridad de la plataforma.

El equipo de Ethical Hacking recibe una autorización formal para realizar las pruebas de seguridad dentro de un alcance previamente definido.

---

## 2. Objetivo del proyecto

El objetivo principal de la evaluación es determinar el nivel de exposición de seguridad de la aplicación web de Aurora Market.

La evaluación busca:

- Identificar vulnerabilidades de seguridad.
- Determinar los riesgos asociados a cada vulnerabilidad.
- Evaluar el posible impacto sobre la aplicación y la información.
- Identificar qué información podría descubrir un atacante.
- Validar de manera controlada los hallazgos encontrados.
- Proporcionar recomendaciones de seguridad.
- Entregar información útil al equipo de desarrollo para su posterior remediación.

---

## 3. Información inicial disponible

Al comenzar la evaluación, Aurora Market proporciona información limitada sobre su infraestructura.

El equipo conoce inicialmente que existe:

- Una aplicación web.
- Una base de datos.
- Mecanismos de autenticación.
- Diferentes tipos de usuarios.

Sin embargo, no se conocen inicialmente todos los detalles técnicos de la plataforma.

Entre la información desconocida se encuentra:

- Tecnologías utilizadas.
- Frameworks.
- Arquitectura de la aplicación.
- Endpoints disponibles.
- Estructura de la base de datos.
- Mecanismos específicos de autenticación.
- Controles de autorización.
- Configuración de seguridad.
- Vulnerabilidades existentes.

Por este motivo, parte importante de la evaluación corresponde a las etapas de **reconocimiento y enumeración**.

---

## 4. Alcance

### Dentro del alcance

La evaluación se realizará exclusivamente sobre:

> **La aplicación web autorizada de Aurora Market.**

Las pruebas estarán orientadas a identificar vulnerabilidades presentes en dicha aplicación y sus funcionalidades asociadas.

### Fuera del alcance

No se permite realizar pruebas sobre:

- Redes sociales de Aurora Market.
- Equipos personales de empleados.
- Cuentas de correo.
- Proveedores externos.
- Sistemas que no formen parte del alcance autorizado.
- Infraestructura o servicios no autorizados.

---

## 5. Reglas de engagement

Las pruebas deberán realizarse respetando las condiciones establecidas por Aurora Market.

### Restricciones principales

- No interrumpir deliberadamente el funcionamiento de la plataforma.
- No afectar información real de los clientes.
- No realizar acciones destructivas.
- No modificar ni eliminar información real.
- No realizar ataques sobre activos fuera del alcance.
- Realizar las pruebas durante horarios de menor actividad.
- Documentar cuidadosamente cualquier problema encontrado.

La finalidad de las pruebas es **evaluar la seguridad**, no generar indisponibilidad ni afectar las operaciones de la empresa.

---

## 6. Metodología de evaluación

La evaluación se desarrollará mediante un proceso controlado de Ethical Hacking.

```text
Reconocimiento
      ↓
Enumeración
      ↓
Identificación de superficie de ataque
      ↓
Análisis de vulnerabilidades
      ↓
Validación controlada
      ↓
Documentación de evidencias
      ↓
Evaluación de impacto
      ↓
Recomendaciones
      ↓
Informe final