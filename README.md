# README

A problem arises when running Ruby on Windows. </br>
I came across several solutions to this problem. </br>
1. Comment out a line in application.js in vendor directory </br>
2. Edit ExecJS in vendor directory </br>
3. Editing a views.html.erb file </br>
4. Install NodeJS </br>
5. Perhaps writing a C extension. </br>
6. User older version of a couple of gems </br>
7. Don't run Ruby on Windows. </br>

I did the Cheap solution, i.e., #3.

Maybe the best thing to do is not the change
any of the exisitng files, and just create
a new class that inherits the the class defined
in the existing files, but rewrite the class.
This way you keep the existing code.

But the problem is that the "name" of the class method
that is being over written ends up being a variable, so
there needs to be a conditional statement.

But re-writing existing gems might have larger effects
that are not immediately apparent.

