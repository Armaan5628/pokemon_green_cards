##  Acknowledgement

During the development of this project, I received assistance from **ChatGPT to help resolve several technical issues related to Flutter configuration, network requests, and deployment setup.  

Originally, the project was intended to use the live **Pokémon TCG API** (`https://pokemontcg.io/`), but due to **CORS restrictions** and connectivity limitations on web builds, I created and hosted a JSON version of the same dataset in my own GitHub repository.  
This allowed the app to successfully fetch, parse, and display Pokémon card data while maintaining the required functionality outlined in the lab instructions.  

All design, integration, and final implementation decisions were done by me, with ChatGPT providing debugging guidance and optimization suggestions.

# Pokémon Green Cards 
A Flutter web & mobile application that displays Pokémon trading cards fetched from an online database.  
Users can view card images with names in a list and tap any card to see a full-screen enlarged view.

---

##  Project Overview
This project was developed as part of a Flutter lab assignment to demonstrate:
- Loading data from an API
- Populating data in a user interface (ListView)
- Handling user interaction (tap to enlarge an image)
- Responsive design for both mobile and web

---

# Features
✅ Fetches Pokémon card data from a hosted JSON API  
✅ Displays card **name** and **image** in a scrollable ListView  
✅ Opens a **full-screen popup** with zoom support when a card is tapped  
✅ Includes **loading indicator**, **error handling**, and **refresh** support  
✅ Fully responsive layout for different screen sizes (mobile, tablet, web)


