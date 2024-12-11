# PROJECT OVERVIEW

* Musiko is an executable program that is especially built for our musicians and composers. Its main goal was to transpose their music sheets on its original keys to their target or desired keys. It offers a quick and dependable way for transposing musical compositions since it was created with speed and accuracy. 

* For musicians who are experimenting with different key changes or playing various instruments, traditional transposition can be an exhausting procedure. By automating the transposition process, Musiko makes it easier for users to quickly and easily switch between keys without requiring any calculations or modifications. In addition, I made this program because I have experienced before traditional way of transposing music sheets and its really time consuming and requires a lot of efforts in order to finish transposing one music sheet. 

* This program was easy to use as well as it is user friendly. Moreover, I believed that by using this system the musicians and the composers can save their time and efforts. Lastly, I believed that their dilemma can be solved by using this system and they can focus on practicing their piece.

# Explanation of how OOP principles were applied
Abstraction 
* The idea of Abstraction is revealing only the most important elements while concealing the system's complexity. Additionally, there are two Abstractions used in Musiko specifically the transposeSheet(String[] musicSheet, String fromKey, String toKey) and transposeNote(String note, int interval). Furthermore, since they only offer the method signature and not the implementation, these methods are abstract. Moreover, MusicTransposer class provides the exact implementation of these functions. Through this way it was only the interface (transposeNote and transposeSheet) shown to the user and it conceals the intricacy of note transposition.

Encapsulation
* I use the encapsulation process on Musiko’s program for combining data and methods that manipulate the data into a single unit. In addition, kindly take note that transposition process was encapsulated in the MusicTransposer. Moreover, the musical notes have their corresponding semitone values that are stored in its private fields such as the notesToSemitones and semitonesToNotes. Furthermore, only public methods like transposeNote and transposeSheet can interact with these fields. Lastly, the Scanner object also encapsulates user input and it process to guarantee that data is handled appropriately within the program.

Inheritance
* I used the inheritance in this program through inheriting its abstract methods like transposeNote and transposeSheet and  the class MusicTransposer extends the abstract class Music. By offering particular implementations of these methods. MusicTransposer class implements its own version of the functionality while inheriting the contract established by the abstract class Music.

Polymorphism
* The Polymorphism is used as well as observed in Musiko’s programs. The transposeNote method of the Music class is overridden by the MusicTransposer class. Additionally,  MusicTransposer gives off a particular implementation for transposing a single note based on a specified duration while the original transposeNote function in the Music class has a general signature like note and intervals. Moreover, Method Overloading is also observed in the MusicTransposer class, there are two variants of transposeNote that are defined throughout this program. The one that accepts a fromKey, toKey, note, and another that accepts a single note and an interval.  In addition, it enables the transposition of notes to be flexible. Also, there is a Runtime Polymorphism in this program there is an instance of polymorphism in the transposeSheet method. Lastly, any array of notes can be used when it is invoked and the transposition behavior is decided at runtime by MusicTransposer's implementation.

# SUSTAINABLE DEVELOPMENT GOALS

Quality Education
* This System make sures that everyone has access to high-quality, inclusive education and encourage possibilities for lifelong learning. In addition to the main objective of this system, a good quality music education can be nurtured by the use of a music transposing system like Musiko. It makes learning easier for the beginners by studying the transposition process. Furthermore, it promotes an equitable learning environment by giving students of all skill levels an specialized tool to comprehend difficult musical courses.

Economic Growth and Decent Work
* Through promoting a full and productive employment, a good quality work for all, and steady, inclusive, and sustainable economic growth. Music educators and musicians may greatly benefit from the system of Musiko. Also, I believed that it could improve their capacity for productive and innovative tasks. Moreover, Musicians can concentrate on other parts and works of their profession like writing, playing, or conducting. Through automating time-consuming processes like transposing. Lastly, it can open up new opportunities in the music industry by providing digital resources for transcription and music instruction.

Reduced Inequality
* Reducing inequality both within and across nations is the goal of my system. Additionally, through offering a fair priced and user-friendly tool for transposing music, the system can solve a problem in music education. Furthermore, This makes it possible for everyone, regardless of financial or geographic locations. Musiko’s systems makes an access to high-quality music education by closing the gap between students from fortunate families and those from less fortunate ones.

Industry, Innovation, and Infrastructure
* Encourage innovation, advance equitable and sustainable industrialization, and construct strong infrastructure. Moreover, it is an instance of digital innovation that can support the expansion of the technology and music education industries is the music transposing system. Moreover, It promotes innovations in educational tools as well as in there aspects and resources by providing an effective tool for transposing music, which could result in new goods or services that benefit the music industries.

Responsible Consumption and Production
* The objective of Musiko is to have a guaranteed sustainable pattern of production and consumption. The system encourages a more environmentally friendly method of teaching and learning by music instructions and learning to digital platforms. Lastly, this system can lessen the environmental effect of traditional music publishing and eliminates the need for tangible items like printed music sheets.

# Instructions for running the program
* Prerequisites:
* Step 1:
Install Java JDK: Download and install the JDK from here if not already installed.
IDE or Text Editor: Use any editor (VSCode, IntelliJ, Notepad++) to write and compile the Java code.
* Step 2:
Create a File:
Open your text editor.
Create a new file named MusicTranspositionApp.java.
Copy and paste the code provided.
* Step 3:
Run the code you’ve copied
* Step 4:
Enter Inputs:
The program will ask for your name, music piece, author, music notes, original key, and target key.
Enter the details as requested.
* Step 5:
Just wait after you filled up
The program will show the transposed music notes and the entire transposed sheet.
