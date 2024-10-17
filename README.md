# **Image Slider**
This project is an Image Slider built using HTML5, CSS3, and JavaScript. It enables users to navigate through a series of images using left and right navigation buttons. The slider is responsive and easy to customize.



### **Features**
- **Image Navigation**: Navigate between images using the left and right buttons.
- **Font Awesome Integration**: Left and right arrows are styled using Font Awesome icons.
- **Responsive Design**: The slider adapts to different screen sizes.
- **Minimalist Design**: Clean and simple interface, ideal for modern web design.



### **Technologies Used**
- **HTML5**: Provides the structure of the slider.
- **CSS3**: Handles the styling of the images and buttons.
- **JavaScript**: Implements the interactive behavior for image navigation.
- **Font Awesome**: Used for the left and right arrow icons.



### **Project Structure**

```
Image-Slider/
│
├── index.html       # The main HTML structure
├── style.css        # CSS file for styling the slider
├── app.js           # JavaScript file for the slider functionality
└── README.md        # Project documentation
```



### **Folder Structure**
- **index.html**: The HTML file contains the image slider layout and navigation buttons.
- **style.css**: This file defines the styling for the image container and the navigation buttons.
- **app.js**: This file includes the JavaScript logic to handle image transitions.
- **README.md**: The project documentation you are currently reading.



### **How to Use**
1. Clone the repository:

```
git clone https://github.com/stephenombuya/ImageSlider
```

2. Navigate to the project directory:

```
cd image-slider
```

3. Open the index.html file in a web browser:

```
open index.html
```

Alternatively, you can open the file directly from your code editor or browser.



### **Customization**
1. Changing the Image Content
To add or change the images in the slider, update the HTML and CSS in the following sections:

- In the app.js file, you can define an array of image paths like this:

```
const images = ['img1.jpg', 'img2.jpg', 'img3.jpg'];
```

- In the style.css file, you can adjust the styling of the images (e.g., dimensions) by modifying the .img-container class:

```
.img-container {
  width: 100%;
  height: 400px; /* Adjust to your desired height */
  position: relative;
}
```

2. Font Awesome Icons
- The left and right arrows use Font Awesome icons. You can customize the icons by changing the i tag classes in the HTML:

```
<i class="fas fa-caret-left"></i> <!-- Left Arrow -->
<i class="fas fa-caret-right"></i> <!-- Right Arrow -->
```

- To change the icons or size, update the classes or use Font Awesome's icon library.

3. Adjusting Button Positions
- You can reposition the left and right buttons by modifying the CSS:

```
.btn-left {
  left: 10px;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}

.btn-right {
  right: 10px;
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
}
```

- Feel free to adjust the left, right, and top values to suit your design.

4. JavaScript Logic
- In the app.js file, the JavaScript handles the slider functionality. Here's a simplified version:

```
const btnLeft = document.querySelector('.btn-left');
const btnRight = document.querySelector('.btn-right');
let currentIndex = 0;

btnLeft.addEventListener('click', () => {
  // Logic for sliding to the previous image
});

btnRight.addEventListener('click', () => {
  // Logic for sliding to the next image
});
```



### **Future Enhancements**
- **Autoplay Feature**: Add an option for the images to automatically slide after a certain interval.
- **Swipe Functionality**: Implement touch events for swipe functionality on mobile devices.
- **Pagination**: Add dots below the slider to indicate the current image and navigate between them.



### **Browser Support**
This project works in all modern web browsers that support JavaScript, CSS3, and HTML5. It is compatible with Chrome, Firefox, Safari, and Edge.



### **Contributing**
Contributions are welcome! If you have ideas for improvements or new features, feel free to fork the repository and submit a pull request. You can also open an issue if you find any bugs or have suggestions.



### **License**
This project is licensed under the Apache License. See the [LICENSE](https://github.com/stephenombuya/ImageSlider/blob/main/LICENSE) file for details.

