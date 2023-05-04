Download Link: https://assignmentchef.com/product/solved-csci213-assignment-1-game-cards-management-system
<br>
<ol>

 <li><strong> Overview </strong></li>

</ol>

This assignment aims to establish a basic familiarity with the JDK development system and its associated on-line Java API class documentation. Students should apply the appropriate fundamental programming concepts (such as variables, constants, arrays, strings, methods, selection and repetition constructs etc.) and make use of appropriate Java API classes (such as Scanner, PrintWriter, String etc.) that they have learnt to solve the given problem.




<ol start="2">

 <li><strong> Objectives </strong></li>

</ol>

On completion of this assignment a student should be able to write simple Java application

that:

<ul>

 <li>Makes use of selection and repetition constructs to achieve desired outcomes</li>

 <li>Stores data to and reads data from arrays</li>

 <li>Generates output to and reads input from the console window</li>

 <li>Reads data from and writes data to text file</li>

 <li>Manipulates string using Java API “String” class</li>

 <li>Handles basic errors</li>

 <li>Applies object-oriented concepts</li>

</ul>




<ol start="3">

 <li><strong> Scope </strong></li>

</ol>

This assignment is based on individual effort. You are required to design, develop and test a Game Cards management system for a game application.

Besides providing the required functionalities, your program should incorporate appropriate error handling. Comments are also to be inserted to improve program clarity. Before you start coding your program, you are strongly advised to carry out proper problem analysis and program design.  You are required to use JDK 1.5 developer version or later.




<ol start="4">

 <li><strong> Requirements</strong></li>

</ol>

This application allows the admin to

<ol>

 <li>Admin login</li>

 <li>Create a game card</li>

 <li>Delete a game card</li>

 <li>Edit a game card information</li>

 <li>Search and display game cards information</li>

 <li>Export game cards information</li>

 <li>Change admin password</li>

 <li>Logout</li>

</ol>







This application will have access to two text files.




The first text file (Admin.dat) contains the administrator-hashed password (SHA-256).

For example

<table>

 <tbody>

  <tr>

   <td width="686">be4b826c27636ab54a8bf15d73fc1bf2a533f547f2343d12a499d45643453ad4</td>

  </tr>

 </tbody>

</table>




The second text file (GameCards.dat) contains the game card information in the following format

&lt;Name&gt;|&lt;Description&gt;|&lt;Earth Element Power&gt;|&lt;Water Element Power&gt;|&lt;Air Element Power&gt;|&lt;Fire Element Power&gt;




For example

<table>

 <tbody>

  <tr>

   <td width="686">Zeus|God of the Sky|30|15|40|15Poseidon|God of the Sea|20|50|15|15Demeter|Goddess of Agriculture|55|25|15|5Ares|God of War|20|10|10|60</td>

  </tr>

 </tbody>

</table>

Note: When a game card is created, all the elements power should add up to 100.




<strong>Error Handling</strong>

Your program should be able to handle error situations. For example where a game card name already existed (for Create a game card) or game card name not found (for delete game card). You should look out for other possible exceptions and handle them too.




For Export game card information requirement, the program should produce a file (GameCardsData.dat) with the following format:

<table>

 <tbody>

  <tr>

   <td width="686">CSCI213 Game Cards Management System Game Card 1Name: ZeusDescription: God of the SkyEarth Element Power: 30Water Element Power: 15Air Element Power: 40Fire Element Power: 15 Game Card 2Name: PoseidonDescription: God of the SeaEarth Element Power: 20Water Element Power: 50Air Element Power: 15Fire Element Power: 15</td>

  </tr>

 </tbody>

</table>


