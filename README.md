# Dietary Product Ingredient Checker 
Grocery shopping can be extra difficult when you’re vegetarian or vegan. Having to read through every ingredient list of every product you’re interested in is really tedious! Then you also have to look up ingredients you are not familiar with to make sure that ingredient is vegan or vegetarian. There’s got to be a better way! Thus we have this project to the rescue. Simply enter in the barcode and select vegan or vegetarian and huzzah! We have a color-coded list of the product's ingredients with non-vegan/non-vegetarian ingredients colored red so that you can know at a quick glance if the product is vegan/vegetarian, making grocery shopping easier and quicker.

Link to live demo of project: https://pokemonlottery.netlify.app/

<p align="center">
  <img src="https://drive.google.com/uc?id=11OWPb1O5ML5x9fqeue6mfV7QmmDZqL37" alt="Product Ingredient Checker home page" />
</p>

<p align="center">
  <img src="https://drive.google.com/uc?id=11-RFJkNiCLeY8WQqpGOEfgwPxGfrAltq" alt="Product Ingredient Checker vegan search example" />
</p>

# How It's Made:
Tech used: HTML, CSS, JavaScript, and APIs

Utilizing the Open Food Facts API, the app sends the user’s search query. When the API responds with the data-set for that product, we clean and narrow down the data to focus on the ingredients. We then loop through each ingredient and check them against the API data to vegan or vegetarian status for every ingredient. Now we’re ready to start making our client side ingredient table that the user will see in the DOM. We dynamically create a table in the DOM then pull the plug in the cleaned data with the needed information into each ingredient row of the table. The app then checks the data values to see if it is or isn’t vegan/vegetarian, dynamically adding the table cells to a CSS class list that corresponds to green (if it is) or red (if it isn’t) backgrounds so our user can more easily visualize the provided information. After doing this for each ingredient, the user can then browse through easily and quickly to verify if the product fits the bill or not. 

# Lessons Learned:
I had a lot of fun with this project as it allowed me to become more efficient in API utilization, sifting through data-sets, rendering dynamically in the DOM,  and manipulating data to one’s needs.

# Other Projects:
Feel free to explore other projects I've worked on:

Pokemon TCG Card Finder: https://github.com/DekotaNelson/pokemon-tcg-lottery

Thought Exchanger for finding and sharing thoughts: https://github.com/DekotaNelson/thought-exchanger

Url shortener Smols Us: https://github.com/DekotaNelson/smols-us

