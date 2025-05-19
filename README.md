# 🚀 Team Challenge U3S12

Ya has completado casi todo el trabajo previo de la unidad y sus workouts, es hora de poner en práctica lo aprendido a través de el **ejercicio obligatorio que harás en la sesión en directo**. 

Este Team Challenge, es un poco diferente a los que has estado haciendo, sigue los siguientes pasos:

1. **Accede a el enlace del Team Challenge:** [[pulsa aquí para acceder]](https://mystery.knightlab.com/)
2. **Lee el contenido** con atención y sigue los pasos que te indican.
3. Una vez resuelto, **vuelve a este espacio** y **responde** a esta actividad con el **resultado** e indica las consultas que has hecho junto con su explicación.

Para entregar el ejercicio del **TEAM CHALLENGE**:

- **Opción 1**
  - Crear un repositorio.
  - Hacer **capturas de pantalla de todas las consultas** y de la **solución**.
  - Subir al repositorio tosas las imágenes y la explicación de cada una.
 
- **Opción 2**
  - Crear un repositorio.
  - Hacer un **documento** (por ejemplo, el Readme) donde van **todas las consultas** y la **solución**.
  - Subir al repositorio el documento.
Si tienes alguna duda contacta con tu LI o con TA para resolverla.

> ## SQL Murder Mystery:
> 
> Can you find out whodunnit?
> 
> ![clue,illustration](/assets/images/clue-illustration.png)
>
> There's been a Murder in SQL City! The SQL Murder Mystery is designed to be both a self-directed lesson to learn SQL concepts and commands and a fun game for experienced SQL users to solve an intriguing crime.

> ### New to SQL?
>
> This exercise is meant more as a way to practice SQL skills than a full tutorial. If you've never used SQL at all, try the walkthrough. If you really want to learn a lot about SQL, you may prefer a complete tutorial like Select Star SQL.
> 
> If you're comfortable with SQL, you can dive in below!

> ## Experienced SQL sleuths start here
> A crime has taken place and the detective needs your help. The detective gave you the crime scene report, but you somehow lost it. You vaguely remember that the crime was a ​murder​ that occurred sometime on ​Jan.15, 2018​ and that it took place in ​SQL City​. Start by retrieving the corresponding crime scene report from the police department’s database.
> 
> ### Exploring the Database Structure
> Experienced SQL users can often use database queries to infer the structure of a database. But each database system has different ways of managing this information. The SQL Murder Mystery is built using SQLite. Use this SQL command to find the tables in the Murder Mystery database.
> Run this query to find the names of the tables in this database.
> This command is specific to SQLite. For other databases, you'll have to learn their specific syntax.
>
> > SELECT name FROM sqlite_master where type = 'table'
> 
> ![query,tables names](/assets/images/img1.png)
>
> Besides knowing the table names, you need to know how each table is structured. The way this works is also dependent upon which database technology you use. Here's how you do it with SQLite.
>
> Run this query to find the structure of the `crime_scene_report` table
Change the value of 'name' to see the structure of the other tables you learned about with the previous query
> > SELECT sql FROM sqlite_master where name = 'crime_scene_report'
>![query,crime_scene_report](/assets/images/img2.png)

> ## The rest is up to you!
> If you're really comfortable with SQL, you can probably get it from here.
>
> But click here to show the schema diagram.
> ![query,crime_scene_report](/assets/images/schema.png)
> And you can always go to the walkthrough.
>
> Use your knowledge of the database schema and SQL commands to find out who committed the murder.
> When you think you know the answer, go to the next section.
>
> ## Resolución:
> 
>> ![step1,screenshot](/assets/images/img3.png)
>> ![step2,screenshot](/assets/images/img4.png)
>> ![step3,screenshot](/assets/images/img5.png)

> ## Check your solution
> Did you find the killer?
>> INSERT INTO solution VALUES (1, 'Insert the name of the person you found here'); SELECT value FROM solution;

> ## Credits
> The SQL Murder Mystery was created by Joon Park and Cathy He while they were Knight Lab fellows. See the GitHub repository for more information.
>
> Adapted and produced for the web by Joe Germuska.
>
> This mystery was inspired by a crime in the neighboring Terminal City.
>
> Web-based SQL is made possible by SQL.js
>
> SQL query custom web components created and released to the public domain by Zi Chong Kao, creator of Select Star SQL.
>
> Detective illustration courtesy of Vectors by Vecteezy
>
> Original code for this project is released under the MIT License
>
> Original text and other content for this project is released under Creative Commons CC BY-SA 4.0 
​
