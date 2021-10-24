## Description
This web application displays the courses I've studied thus far at Miun. 
The courses are stored in a MySQL database and the application uses a PHP REST API 
to communicate with the database. It is also possible to add, delete and edit courses.
Refresh the browser in order to see the changes you've made. The application can be found [here](http://studenter.miun.se/~mazi2001/writeable/dt173g/moment5/webbplats/index.html) as well as on [GitHub Pages](https://marzin89.github.io/miun-courses/index.html).
### Adding courses
Adding a course requires the following information:
- Course code (_Kurskod_)
- Course name (_Kursnamn_)
- Course progression (_Progression_, should be either A or B)
- Course syllabus (_Kursplan_, should be an URL)
Fill in all the required fields and click _Skicka_ in order to add the course.
### Editing courses
In order to edit a course, click _Ändra_ below the course syllabus link.
Fill in all the required fields (see _Adding courses_) and click _Skicka_.
### Deleting courses
Click _Radera_ below the course syllabus link.
