# netflix-clone-PHP-noframework-project
Netflix clone project with Udemy course, no framework, PHP and JS</br>
These are the projects Ive done some time ago with Udemy courses and now I re-visit them, document my work, evaluate the code etc. </br>
These are good courses and Ive learnt a lot from them. Since I was too busy to document my work in past (for job searching) Im building my portfolio right now </br>
Here is link to a course: https://www.udemy.com/course/netflix-clone/ </br>

# Weaknesses: </br>
- dsn begs for some .env file</br>
- lengthy imports beg for some autoloading feature </br>
- api routes beg for some http method check and cors</br>
- parameters bound to PDO queries beg for providing third argument, which is the type</br>
- It could be nice idea to introduce some design patterns to the project </br>
- Use of sizeof() alias for count() function is bad in my opinion</br>
- Im not so sure about searching DB, fetching results and then creating html elements (as strings) on the server side.
There are some potential possibilities of use PHP built-in DomDocument class OR one can use JSON to send data to frontend to create elements there </br>
- Im not so sure about <strong>$(".results").html(data);</strong>. In my opinion it is best to avoid using .html() or innerHTML if we mean vanilla JS - i would double-check, .html() is always red alert for me. Besides, JS has a lot of features to create document fragments, text nodes and html nodes and appending them to the body </br>
- Still, it is a great project and serves its purpose as Udemy course teaching a lot of things. Im proud I completed this task </br>

# Strengths: </br>
- OOP, well-named classes and methods, classes arent too lengthy</br>
- project does A LOT: frontend, db connection, API for ajax, PayPal integration... </br>
- Idea of using error-array that is standard (even nowadays one can find a 'help' that displays first error found. Like, username too short but if the passwords dont match, i will
tell you on next resubmit that) </br>
- Uses PDO, binding parameters </br>
- Uses sanitizers and validators </br>
- Pretty well-structured pure PHP project </br>
- Good CSS, good UI/UX frontend experience </br>
- sha512 hash is always better that md5 :) </br>
- Error handling </br>
- Generally, very good project </br>
