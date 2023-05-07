Download Link: https://assignmentchef.com/product/solved-natural-language-assignment-1-an-eliza-program-in-perl
<br>
To gain experience with the Perl programming language, in particular the use of regular expressions in order to do “word spotting” and transform sentences from answers into questions. To gain an appreciation for the difficulties of natural language processing in general.




<strong>Specification</strong>

<strong>Write an Eliza program in Perl. The program should be called eliza.pl, and it should run from the command line with no arguments.</strong>

Your program should engage in a dialogue with the user, with your program Eliza playing the role of a psychotherapist. Your program should be able carry out “word spotting”, that is it should recognize certain key words and respond simply based on that word being present in the input. It should also be able to transform certain simple sentence forms from statements (from the user) into questions (that Eliza will ask). Also, try to personalize the dialogue by asking and using the user’s name.

Here’s the start of an example dialogue…

eliza.pl

-&gt; [eliza] Hi, I’m a psychotherapist. What is your name?

=&gt; [user] My name is Bridget.

-&gt; [eliza] Hi Bridget. How can I help you today?

=&gt; [Bridget] I want to rule the world.

-&gt; [eliza] Bridget, why do you want to rule the world? [transform statement into ?]

=&gt; [Bridget] I don’t know, I think I crave power.

-&gt; [eliza] Why don’t you tell me more about your cravings. [word spot “crave” and respond.]

=&gt; [Bridget] …

Your program should be robust. If the user inputs gibberish or a very complicated question, Eliza should respond in some plausible way (I didn’t quite understand, can you say that another way, etc.)

<strong>This program should rely heavily on the use of regular expressions</strong>, so please make sure to review some introductory material in Learning Perl, Programming Perl, or some other source before attempting this program.

Eliza examples:

<ul>

 <li>start emacs and run “M-x doctor”</li>

 <li>eliza on the web</li>

 <li>another eliza on the web</li>

</ul>

Policies (see syllabus for more details)

<strong>Please comment your code.</strong> In particular, explain what words you are spotting for (and why) and what statement forms you are converting into questions (and why). Also make sure you name, class, etc. is clearly included in the comments.

<strong>It is fine to use a Perl reference book for examples of loops, variables, etc., but your Eliza specific code must be your own, and not taken from any other source (human, published, on the web, etc.)</strong>