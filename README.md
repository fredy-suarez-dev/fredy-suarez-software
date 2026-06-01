## 🏗️ Filosofía de Desarrollo & Arquitectura

En mis desarrollos backend con **Java y Spring Boot**, priorizo la mantenibilidad, la resiliencia y el desacoplamiento de la lógica de negocio. Por ello, aplico **Arquitectura Hexagonal (Puertos y Adaptadores)** y principios **SOLID**.

<p align="center">
  <img src="https://raw.githubusercontent.com/fredy-suarez-software/hexagonal/master/src/img/arquitectura_hexagonal.png" alt="Arquitectura Hexagonal" width="650"/>
</p>

### 🔍 ¿Cómo estructuro mis proyectos?
*   **Dominio (Core):** Contiene las entidades de negocio y las reglas más puras de la aplicación, totalmente aisladas de frameworks externos.
*   **Puertos (Interfaces):** Definen el contrato de comunicación (qué operaciones se pueden hacer), tanto para la entrada de datos como para la salida hacia servicios externos.
*   **Adaptadores (Infraestructura):** Implementaciones tecnológicas concretas (controladores REST de Spring, persistencia con JPA/Hibernate en MySQL/Oracle, mensajería, etc.).

### Backend Developer | Java Enthusiast 🚀

Me apasiona construir soluciones escalables y eficientes en el lado del servidor. Actualmente me enfoco en el ecosistema de Java para crear APIs robustas y arquitecturas limpias.

---

### 🛠️ Mi Stack Tecnológico

- **Lenguajes:** Java (8, 11, 17+)
- **Arquitectura:** Hexagonal, Patrones de Diseño (SOLID)
- **Bases de Datos:** MySQL, SQLServer, Oracle
- **Herramientas:** Git, Docker

---

### 🛠️ Tecnologías

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://custom-icon-badges.demolab.com/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=mssqlserver-white&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-black.svg?style=for-the-badge)
---

### 📫 Contacto

- **Email:** fredysuarez.software@gmail.com

---

🚀 Mi Camino de Aprendizaje (Roadmap)
Actualmente estoy evolucionando un proyecto de **Gestión de Usuarios** para demostrar
diferentes niveles de madurez técnica:
- **Nivel 1:** Arquitectura Hexagonal con Java Puro (Lógica de negocio sólida).
- **Nivel 2:** Implementación de Maven (Gestión profesional de dependencias).
- **Nivel 3:** Transformación a API REST con Spring Boot 3 y persistencia real.

---

### 🚀 Evolución del Proyecto: Gestión de Usuarios


| Característica / Nivel | Nivel 1: Java Puro ☕ | Nivel 2: Maven 📦 | Nivel 3: Spring Boot 3 🌱 |
| :--- | :--- | :--- | :--- |
| **Repositorio** | [`hexagonal`](https://github.com/fredy-suarez-dev/hexagonal) | [`hexagonal-maven`](https://github.com/fredy-suarez-dev/hexagonal-maven) | [`hexagonal-spring-boot`](https://github.com/fredy-suarez-dev/hexagonal-spring-boot) |
| **Arquitectura** | Hexagonal estricta | Hexagonal estricta | Hexagonal adaptada a Framework |
| **Gestión de Dependencias** | Manual (Sin herramientas) | Maven (`pom.xml`) | Maven + Spring Boot Starters |
| **Interfaz de Usuario / Entrada** | Consola / Pruebas unitarias | Consola / Pruebas unitarias | API REST (Controladores HTTP) |
| **Persistencia (Datos)** | En Memoria (Listas/Mapas) | En Memoria (Listas/Mapas) | Base de Datos Real (JPA / Hibernate) |
| **Servidor de Aplicaciones** | No requiere | No requiere | Servidor embebido (Tomcat) |

---
