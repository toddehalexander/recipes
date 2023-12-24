<style>
  .image-collage {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 10px; /* Adjust the gap as needed */
  }

  .image-collage a {
      display: flex;
      justify-content: center; /* Center the images within the anchor elements */
  }

</style>


# Recipe Generator App


<div class="image-collage">
  <a href="Screenshots/Recipe1.png"><img src="Screenshots/Recipe1.png" alt="Recipe 1"></a>
  <a href="Screenshots/Recipe2.png"><img src="Screenshots/Recipe2.png" alt="Recipe 2"></a>
  <a href="Screenshots/Recipe3.png"><img src="Screenshots/Recipe3.png" alt="Recipe 3"></a>
  <a href="Screenshots/Recipe4.png"><img src="Screenshots/Recipe4.png" alt="Recipe 4"></a>
  <a href="Screenshots/Recipe5.png"><img src="Screenshots/Recipe5.png" alt="Recipe 5"></a>
  <a href="Screenshots/Recipe6.png"><img src="Screenshots/Recipe6.png" alt="Recipe 6"></a>
</div>

## Api Used
[Visit The Meal DB](https://www.themealdb.com/api.php)

## Overview
The Recipe Generator app is an iOS application developed using SwiftUI, providing users with a seamless experience to explore and discover recipes based on various categories. The app's intuitive interface allows users to select a specific category, view a list of recipes within that category, and seamlessly navigate through the content.

## Features

### Category Selection
Users can choose a recipe category from a visually appealing grid layout on the main screen.

### Dynamic Navigation
Tapping on a category navigates users to a detailed list of recipes within that category.

### Image Loading
Recipe category thumbnails are loaded asynchronously to ensure a smooth user experience.

### Shopping Cart Integration
Users can access their shopping cart by tapping on the cart icon in the navigation bar.

## Project Structure
- **ContentView.swift:** The main view of the app, including the category selection grid and navigation.
- **APIManager.swift:** Handles the fetching of meal categories from a backend API.
- **ShoppingCartView.swift:** Displays the contents of the user's shopping cart.
- **AsyncImage.swift:** A custom SwiftUI view for loading images asynchronously.
- **Extensions.swift:** Contains an extension for UIColor to initialize colors using hexadecimal values.

## Customization

### Theming
The app features a customized navigation bar appearance with a gray background color and contrasting title text attributes. The appearance is set in the `init()` method of ContentView.

### Color Extension
The UIColor extension allows easy creation of colors using hexadecimal values, providing flexibility for customizing the app's color scheme.

## Usage
1. Clone the repository.
2. Open the project in Xcode.
3. Build and run the app on a simulator or physical device.

Feel free to explore, customize, and enhance the app to meet your specific requirements! If you encounter any issues or have suggestions for improvement, please let us know. Happy cooking!
