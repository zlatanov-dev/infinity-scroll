README

Try it out! - https://infinite-scroll.github.io/

This is a simple web app that fetches and displays photos from the Unsplash API in an infinite scroll fashion. It loads an initial set of photos on page load and then fetches additional photos as the user scrolls down the page.
Installation


How it works

When the page loads, the getPhotos() function is called which fetches a set of random photos from the Unsplash API using the apiKey variable. The fetched photos are then displayed on the page using the displayPhotos() function.

As the user scrolls down the page, the window event listener checks if the user has reached the bottom of the page and if so, it calls the getPhotos() function again to fetch and display more photos.

The setAttributes() function is a helper function used to set attributes on DOM elements.
