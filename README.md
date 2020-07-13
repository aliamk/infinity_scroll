# infinity_scroll
https://aliamk.github.io/infinity_scroll/


  1) Went to site loading.io and chose a free loader design.  Played with it's colours/size etc.  Set it to transparent. Downloaded it as an animated SVG.  Placed it within the project folder.  

  2) Picked a Google font and used the @import method to bring it into CSS.  Added a H1 title to test font.  Changed bground colour to whitesmoke.  

  3) Added a loader class and img src="loader.svg" in index.html to display the loader. In CSS, added centering properties.

  4) Added a responsive layout for large smartphone viewing. Reduced title font-size and left-right margins.

  5) Created a new project application on Unsplash Developer and got an API key.  Created a fetch request.

  6) Create a Global variable called photosArray which is empty... will pass API data into this empty array. The displayPhotos() function will call on the photosArray variable and run a forEach method on it.  This will generate html elements based on the data requested from the API (photo link, photo size, photo alt description and photo title)

  7) Currently, we've set the app to load a max of 10 photos from the API.  We want it to be a greater number but for that we need better functionality:  we don't want the user to reach photo 10 at the bottom and then have to wait for more photos to load.  We use the DOM's scroll event listener on the window object.
