# Event-Registration-System-Management
Registration System

---

## README / Run steps (line-by-line)

1. Install MySQL and create user/password.
2. Update src/main/resources/db.properties with your DB credentials.
3. Run the SQL in sql/schema.sql to create db and seed events.
4. Build the project: mvn clean package
5. Deploy the generated WAR (target/event-registration-1.0-SNAPSHOT.war) to a Servlet container (Tomcat 10+ or any Jakarta EE 9+ container).
6. Access the app at http://localhost:8080/event-registration/ (or /event-registration/events)


---

If you'd like, I can:
- export this as a downloadable ZIP
- add email confirmation (SMTP) code
- add admin authentication and an admin UI
- convert the DAO to use a connection pool (HikariCP)

Tell me which next step you prefer.
By
