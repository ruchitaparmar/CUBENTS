## Introduction
- The project was accomplished as a part of The National Mission on Education through ICT. 
- CUBENTS is a web application which consists of an interactive whiteboard. 
- It stands for <b>C</b>omprehensive <b>U</b>tility <b>B</b>oard for <b>E</b>quatio<b>N</b> <b>T</b>ext and <b>S</b>hapes. 

## What is CUBENTS?
- The primary aim of the board is for teachers to be able to create lessons for students.
    - The board includes an inbuilt equation parser which makes typing complex equations simpler for teachers. Be it double             integration formulae or continuity and limits. The parser uses <a href="https://en.wikipedia.org/wiki/MathML"                     target='_blank'>MathML</a> to add mathematical tags such as superscript or subscript to the variables and numbers entered         by the user. 
    - Users can also draw objects such as pulleys or blocks using basic shapes to demonstrate examples in the lesson. A                 JavaScript framework called <a href="http://fabricjs.com/" target='_blank'>Fabric.js</a> has been used for creating               flexible sized shapes. 
    - Users can also add text boxes to write titles and descriptions. 
    - All of these features can be given entry or exit animation effects with an animation order. 
    - The user can finally name the lesson and save it. This parses all the data into a JSON object and store it in a                   database using MySQL. 
    - The student can now view the entire presentation by looking up the name of the lesson in the lesson tree. 
    - The application can be viewed <a href="http://codebank.org.in/" target='_blank'>here.</a>
    - Go to the <a href="http://maths.codebank.org.in/LearnerView?url=EditorView.jsp" target='_blank'>editor</a> mode to create         lessons or go to the <a href="http://maths.codebank.org.in/LearnerView?url=LearnerView.jsp" target='_blank'>learner               mode</a> to view lessons.
    - For more help, read click on the click on the User Manual at the top left corner of the web application.
