# Image Search App

This project is an Image Search App that utilizes the Unsplash API to fetch images based on user input. Users can specify what kind of pictures they wish to see, and the app displays a curated selection of images accordingly. The application is built using HTML, CSS, and JavaScript.

## How it Works

The app sends a request to the Unsplash API with the user's input as the search query. The API returns a collection of relevant images, which are then displayed on the site. Approximately 9-12 images are shown initially, and additional images can be loaded by clicking the "Show More" button.

## Usage

To use the Image Search App:

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser.
3. Enter your desired search query in the input field.
4. Press Enter or click the search button to see the images.
5. Scroll through the images or click the "Show More" button to load additional images.

## Technologies Used

- HTML
- CSS
- JavaScript

## API Used

This project utilizes the Unsplash API to fetch images. To use the API, you need to obtain an access key from Unsplash. The access key should be added to the API request URL in the JavaScript code.

```javascript
const url = `https://api.unsplash.com/search/photos?page=${page}&query=${inputData}&client_id=${accessKey}`;
```

Replace `${page}` with the page number, `${inputData}` with the user's search query, and `${accessKey}` with your Unsplash API access key.

## Credits

This project was created by Sona Varshney. You can find more of my work on [GitHub](https://github.com/SonaVarshney).

