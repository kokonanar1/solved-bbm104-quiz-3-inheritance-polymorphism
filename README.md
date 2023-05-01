Download Link: https://assignmentchef.com/product/solved-bbm104-quiz-3-inheritance-polymorphism
<br>
Write an object oriented program that creates the standing tables from the given all matches result separately of the Ice Hockey and Handball sports.

<strong>1.1 Information about the sports </strong>• In Ice Hockey, in which three points are awarded to the team winning a match, with no points awarded to the losing team. If the game is drawn, each team receives one point. • In Handball, in which two points are awarded to the team winning a match, with no points awarded to the losing team. If the game is drawn, each team receives one point. • If two or more teams are on the same number of points. The number of goals scored against a team is subtracted from the number of goals it has scored itself. The bigger the goal difference, the better.

<h2>1.2         Restrictions</h2>

<ul>

 <li>You must implement your codes by using inheritance and polymorphism.</li>

 <li>There are 4 teams in each sport type.</li>

 <li>The initial scores of the 4 teams in each sport type are zero. Since each group has 4 teams separately, there will be 6 match totally in each group. Therefore, there are 12 match (fixed 12 lines) totally in fixtures.txt</li>

</ul>

1

<h2>1.3         Sample Input and Outputs</h2>

<ul>

 <li>Sample input file named as fixtures.txt:</li>

</ul>

[<strong>First letter of sport</strong>]tab[<strong>name of first club</strong>]tab[<strong>name of second club</strong>]tab[<strong>match result</strong>]newline

<ul>

 <li>Sample output files.</li>

</ul>

[<strong>ranking.</strong>]tab[<strong>name of club</strong>]tab[<strong>number of played matches</strong>]tab[<strong>number of matches won </strong>]tab[<strong>match with an even score or tie</strong>]tab[<strong>number of matches loss </strong>]tab[<strong>number of sets For:the number of sets Against </strong>]tab[<strong>total points</strong>]newline

<ul>

 <li>txt is as shown below:</li>

</ul>

Figure 2: handball.txt

<ul>

 <li>txt is as shown below</li>

</ul>

Figure 3: icehockey.txt

<ul>

 <li>You are expected to write the output of your program to a text file named type of sport.txt for each type of sport. (for example: icehockey.txt, handball.txt.)</li>

 <li>The explanation of the standing table columns for each sport types are as follows:

  <ul>

   <li>First column defines the ranking</li>

   <li>Second column defines the club name</li>

   <li>Third column defines the number of played matches</li>

   <li>Fourth column defines the number of matches won</li>

   <li>Fifth column defines the number of times a team has finished a match with an even score or tie</li>

   <li>Sixth column defines the number of matches loss</li>

   <li>Seventh column defines the number of sets For : the number of sets Against</li>

   <li>Eighth column defines the total number of points earned</li>

  </ul></li>

</ul>

<h1>2           How to run your program</h1>

The input file is going to be given as program argument. In order to test your program, you should follow the following steps:

<ul>

 <li>Upload your java files to your server account (dev.cs.hacettepe.edu.tr)</li>

 <li>Compile your code (javac *.java) Run your program (java Main fixtures.txt)</li>

 <li>Control your output data and format.</li>

</ul>

<strong>P.S. Output files (handball.txt, icehockey.txt) will be evaluated automatically. So, please be careful about the format of output files and be sure that they are exactly same with the output files as we have shared.</strong>