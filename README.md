# README

Ruby on Rails Tutorial (Rails 5) Learn Web Development with Rails
Michael Hartl


Exercises (1.3.4)

    1. Change the content of the hello action in Listing 1.8 to read “hola, mundo!” instead of “hello, world!”.
    2. Show that Rails supports non-ASCII characters by including an inverted exclamation point,
       as in “¡Hola, mundo!” (Figure 1.13).17 To get a ¡ character on a Mac, you can use Option-1;
       otherwise, you can always copy-and-paste the character into your editor.
    3. By following the example of the hello action in Listing 1.8, add a second action called 
       goodbye that renders the text “goodbye, world!”. Edit the routes file from Listing 1.10 
       so that the root route goes to goodbye instead of to hello (Figure 1.14). 
       
Exercises (1.5.3)
       
    1. Solutions to exercises are available for free at railstutorial.org/solutions with 
    any Rails Tutorial purchase. To see other people’s answers and to record your own, 
    join the Learn Enough Society at learnenough.com/society.
       
    2. By making the same change as in Section 1.3.4.1, arrange for your production app to display “hola, mundo!”.
    As in Section 1.3.4.1, arrange for the root route to display the result 
    of the goodbye action. When deploying, confirm that you can omit master in the Git push, as in git push heroku. 