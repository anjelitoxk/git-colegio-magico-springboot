# 📝 Plantilla de Entrega: El Pensadero

**Estudiante:** Ángel Orlando Briceño Chacón

1. **¿Usaste Inteligencia Artificial para resolver los retos (del 1 al 4)?**
   *Respuesta:* Sí, utilicé Inteligencia Artificial como asistente y copiloto de programación durante el desarrollo de los retos.

2. **¿Para qué específicamente te fue útil la IA? (Ej. para entender la lógica de las anotaciones, para explicar los errores de Java, para que hiciera el código desde cero)**
   *Respuesta:* Fue especialmente útil para comprender el propósito de cada anotación JPA y Jakarta (`@Entity`, `@Table`, `@Id`, `@Repository`, `@Service`, `@Transactional`, `@Path`, `@POST`, `@GET`, `@QueryParam`), entender la estructura de la arquitectura por capas, diagnosticar y depurar errores en las pruebas unitarias locales, y asegurar buenas prácticas en la sanitización de consultas JPQL contra inyecciones SQL.

3. **¿Qué fue lo que más se te dificultó al trabajar con la Arquitectura por Capas en Spring Boot?**
   *Respuesta:* Comprender la separación estricta de responsabilidades entre la capa de acceso a datos (DAO/Repository), la capa de negocio (Manager) y la capa de exposición HTTP (Services/Controllers), asegurando que cada una maneje adecuadamente sus propias validaciones, tipos de retorno, transacciones y control de excepciones (como diferenciar un error de validación de negocio de un fallo de persistencia).

4. **¿Qué aprendiste sobre la creación de APIs REST y el uso de Jakarta en esta academia?**
   *Respuesta:* Aprendí a mapear entidades relacionales a objetos Java usando Jakarta Persistence (JPA), a construir y exponer endpoints HTTP RESTful asociando los verbos adecuados (`GET`, `POST`), a capturar parámetros de URL con `@QueryParam`, a responder con códigos de estado HTTP semánticos y profesionales (`201 CREATED`, `400 BAD REQUEST`, `200 OK`) y a estructurar un backend robusto, modular y escalable con Spring Boot.
