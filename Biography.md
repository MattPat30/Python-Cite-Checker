# Python-Cite-Checker
Python Cite Checker made for Suffolk Law Review in connection with the Suffolk University Law School class Coding the Law.  Anaconda is needed to run this program, which can be downloaded at https://www.anaconda.com/products/individual#Downloads

A private youtube video catalouging the development is available for viewing at https://www.youtube.com/watch?v=odfp6NNCU58.  Please contact mpatalano@suffolk.edu for access.


The below is to address the main grading criteria for this project.

# Framing
My client was Suffolk Law Review.  From the beginning, my goal was to improve the citechecking process.  Although we could have attempted to help make the process faster, it was clear that the client was more concerned with making a product that could prevent cite checker error.  This allowed me to focus future issues on resolving this issue.
# Research
I began by looking at the current solutions available to the client.  It was clear that the status quo was not sufficent because mistakes were being made, and a "store bought" cite checker could not be narrowly tailored to Suffolk Law Review's grammatical rules.  I soon settled on making a program that would be able to use regular expressions to find errors, which lead me to either Word Macros or a Python Program.  I ultimately settled on a Python Program because Word does not have a sufficently advanced regular expression capability.
# Ideation & Prototyping
The first ideatopm was with a Word Macro because I thought this would be more user friendly.  The regular expressions offered by Word were not robust enough and in order to make a product that did robust cite checking, I ultimately settled on making a python program.  Through trial and error (see python notebook) I was able to add one rule at a time to make a usable program.
# User Testing
Although I will continue to test, at the time of this submission there have been three user testing phases.  The first phase, conducted while the product was in development, consisted of user observation.  Users observed as I used the program.  Informal feedback was requested and collected and devolpment was tailored based on feedback.  The second phase of user testing was guided user testing.  After MVP was achieved, Users were instructed on how to use the app and were observed using it.  My observations and informal feedback lead to alterations in design.  The final and current stage of user testing is non guided user testing.  Users are using the app without guidance and responding to a google form.  User responses at the time of this entry are on the spreadsheet titled Python Cite Checker (Responses).  User testing will likely continue into the spring
# Refinement
As discussed, it was necessary to switch to Python.  Ultimately, this meant that the end user would likely be the Associate Production Editor of Law Review (my current role) instead of being any and all staffers.  Additionally, as I continued to prototype it was important to pick which rules to work on based on user feedback.  After feedback, I decided it was necessary to add the 3id rule to my project, which required adding a counter that was able to look across multiple paragraphs before making a determination.  After this I continued to focus on projects that the client had requested as to give them as robust a tool as possible.
# Intro Pitch
During my intro pitch, I described who Suffolk Law Review was, I presented the common issue facing law review (mistakes during citechecking), I showed how the current options do not safeguard sufficiently against mistakes, and I described my current plans for confronting cite checking mistakes (using a regular expression to catch common mistakes).
# Complexity/Robustness
During this project, I used expert systems (Python, Python-docx, Regular expressions) to scrape information from other students’ notes and comments and produced an automated document.
# Impact & Efficiencies
This project decreases the amount of time spent on cite checking by over 50%.  By preventing mistakes early in the writing process, students are not forced to expend significant amounts of time on corrections.  The Python cite checker currently checks for 6 rules, thus saving cite checkers time from having to check those rules.  Additionally, this could grow in future and save more time.
# Sustainability
This project is sustainable and expandable.  No modifications need to be made unless the bluebook changes, which is exceedingly rare.  There is a document explaining how to expand the Python Cite Checker if a future student is interested in doing so.  Future Law Review members should have all the tools they need to use this without modification for a long time.
# Fit/Completeness
The final result produces a document that flags any bluebook errors that the program is trained to look at: [Only 2 spaces (no more or less) after :] [Only 1 spaces (no more or less) after ;] [Federal should only be capitalized if the word it modifies is capital] [Ellipse periods must be separated by a space] [No prohibited words in blurbs] [3 id rule].  It also produces a word document that users can “check off.”  Word document also contains original text with Footnote and paragraph markers that helps users identify errors.  
# Real World Viability
I definetly feel that this project has exceeded Law Review's expectations and can be used today to save them time.  The project works in its current form and can be used by Law Review as needed.
# Documentation
I have produced a word document that helps users add new rules if they can create the appropriate regular expression.  Additionally, users are given instructions on how to "start" the program, are told what rules the program checks for, and how to modify their documents to a way the app can use.  Finally, users are given instructions on how to interpret the results document.
# Final Thoughts
This was a great project that I had a lot of fun working on and I will definetly be using python again soon.  I think Law Review is happy with what I produced and I am too.
