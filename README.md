Download Link: https://assignmentchef.com/product/solved-swen221-lab-8-subtle-aspects-of-encapsulation
<br>
The purpose of this lab is to explore some subtle aspects of encapsulation. In particular, a program is given which appears (for the most part) to be properly encapsulated. However, there remain certain ways in which code can break encapsulation.

<h2>1      RobotWar</h2>

A small software program, called Robot War, is provided which implements a battle arena in which robot with <em>artificial intelligence </em>can compete against each other.

You can download the robotwar.jar from the lecture schedule on the course home page. You should begin by running the software and getting a feel for how it works. Figure 1 shows a screenshot from RobotWar.

<h2>2       What to do</h2>

You should find that a number of the <em>invalid </em>tests are failing. Your job is to harden the robot war code base against the attempts to break encapsulation embodied in the invalid tests. <strong>Please note that just changing the test code is insufficient for this lab</strong>. Rather, you instead need to ensure certain objects do not give away as much information as they currently are.

<h2>Submission</h2>

Your lab solution should be submitted electronically via the <em>online submission system</em>, linked from the course homepage. The required files are:

robotwar/core/Robot.java robotwar/core/Battle.java robotwar/core/Action.java robotwar/util/Position.java robotwar/actions/Shoot.java robotwar/actions/Move.java robotwar/robots/PatrolBot.java

1

Figure 1: A screenshot from the robot war game.

You must ensure your submission meets the following requirements (which are needed for the automatic marking script):

<ol>

 <li><strong>Your submission is packaged into a jar file, including the source code</strong>. <em>Note, the jar file does not need to be executable</em>. See the following Eclipse tutorials for more on this:</li>

</ol>

http://ecs.victoria.ac.nz/Support/TechNoteEclipseTutorials

<ol start="2">

 <li><strong>The names of all classes, methods and packages remain unchanged</strong>. That is, you may add new classes and/or new methods and you may modify the body of existing methods. However, you may not change the name of any existing class, method or package. <em>This is to ensure the automatic marking script can test your code</em>.</li>

 <li><strong>All JUnit test files supplied for the assignment remain unchanged. </strong>Specifically, you cannot alter the way in which your code is tested as the marking script relies on this. This does not prohibit you from adding new tests, as you can still create additional JUnit test files. <em>This is to ensure the automatic marking script can test your code</em>.</li>

 <li><strong>You have removed any debugging code that produces output, or otherwise affects the computation. </strong><em>This ensures the output seen by the automatic marking script does not include spurious information</em>.</li>

</ol>

<strong>Note: </strong>Failure to meet these requirements could result in your submission being reject by the submission system and/or zero marks being awarded.