

To run this application open index.html in a compatable browser Fixes to views/js/main.js include:

    Creted var elem = ""; outside of forloop
    Changed variables set by class to getElementsByClassName
    Limited number of pizzas being generated for background
    When generating pizzas im adding them to a documentfragment and then appending it to the randompizza div
    changePizzaSizes size is calculated outside the forloop since each pizzas size before change should be the same


