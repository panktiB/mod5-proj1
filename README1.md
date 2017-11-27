HOW TO USE THIS APPLICATION

1) Clone repository
	move into the local folder you want to save the file to and type the following command :
	git clone https://github.com/panktiB/mod5-proj1.git
   the application is now available on your machine.

2) Or you can download the zip files and extract the contents.

Now that the files are available to you on your machine, you can open index.html on your browser and the app opens up. 
There are many links on the apps page such as a link to a game, aa class on website optimization, a pizza site etc.

--------------------CHANGES MADE-------------------

INDEX.HTML
Line 14 - inline css 
Line 76-include async attribute
Line 66-include print media attribute
Line 112- resize the pizzeria image
Line 124-use web font loader to load fonts using javascript and delete google font api stylesheet link from head


VIEWS/PIZZA.HTML
Line 5 - inline css/style.css

VIEWS/MAIN.JS
Line 407 - move the query selector outside the switch case and use document.getElementById() which is faster
Line 554 - move the sizing switch case from determineDx() function into the changePizzaSizes() function
Line 457 - change the decimals to % and remove return statements
Line 468 - move the document.querySelectorAll() outside the loop and change to document.getElementsByClassName()
Line 469 - save the length of array outside the loop so it is not accesed each time loop is run
Line 472 - remove the call to the determineDx() function it is no longer necessary
Line 488 - declare pizzasDiv outside the loop
Line 522 - document.getElementsByClassName() is faster than document.querySelectorALL()
Line 523 - declare variable scrollTop outside the loop
Line 524 - declare an empty array for phase calculation
Line 527 - due to %5 operator there are only 5 different values for phase. whatever i may be, i%5 will always be from 0 to 4. so we split the loop into two, one for phase from 0 to 4 and one for positions that is 0 to items.length.
Line 530 - save the array length outside loop so it is not accesed at every run
Line 551 - calculate the height of screen and calculate number of pizzas required to fill the screen
Line 555 - calculating the number of pizzas required
Line 556 - declare variable move initialised with document.getElementById() outside the loop
Line 557 - declare elem outside the loop so its not created in every run
Line 558 - reducing the number of pizzas by dynamically calculating the correct number required