# **🏞️ Background Remover**

A simple and interactive web tool to remove the background from your images instantly. This project uses HTML, CSS, and JavaScript to capture user uploads and integrates with the [Remove.bg API](https://www.remove.bg/) to process the images.

## **✨ Features**

* **Drag & Drop Upload:** Easily drag and drop your image files onto the uploader.  
* **Click to Upload:** A traditional file input is also available.  
* **Instant Processing:** Sends the image to the API and gets the result in seconds.  
* **Interactive Comparison Slider:** A "Before vs. After" slider to easily compare the original image with the background-removed version.  
* **Download Result:** Download the new image with a transparent background as a PNG.  
* **Fully Responsive:** Looks and works great on both desktop and mobile devices.  
* **FAQ Section:** A simple, expandable FAQ section to answer common questions.  
* **Client-Side Validation:** Checks for valid file types (JPEG, PNG, WEBP) and size (10MB max) before uploading.

## **🛠️ Technologies Used**

* **HTML5:** For the core structure and layout.  
* **CSS3:** For all styling, including the interactive slider and responsive design.  
* **JavaScript (ES6+):** For all client-side logic, including:  
  * Drag & Drop functionality  
  * File validation  
  * API fetch requests  
  * Interactive comparison slider logic  
  * DOM manipulation  
* **Remove.bg API:** The external service used to process the images and remove the background.

## **🚀 How to Use**

To run this project locally, you just need a modern web browser and your own API key.

1. **Clone the repository:**  
   git clone \[https://github.com/your-username/background-remover.git\](https://github.com/your-username/background-remover.git)

2. **Navigate to the project directory:**  
   cd background-remover

3. **Get your API Key:**  
   * Go to [www.remove.bg/api](https://www.remove.bg/api)  
   * Sign up for a free account.  
   * Find your API Key in your account dashboard.  
4. **Add your API Key:**  
   * Open the script.js (or equivalent JavaScript) file.  
   * Find the following line (around line 12):  
     const API\_KEY \= 'YOUR\_API\_KEY\_GOES\_HERE';

   * Replace YOUR\_API\_KEY\_GOES\_HERE with the actual API key you got in the previous step.  
5. **Open the app:**  
   * Simply open the index.html file in your favorite web browser (like Chrome, Firefox, or Edge).  
   * You can now upload images and test the functionality.

## **🤝 Contributing**

Contributions, issues, and feature requests are welcome\! Feel free to check the [issues page](https://www.google.com/search?q=https://github.com/your-username/background-remover/issues).

## **📄 License**

This project is licensed under the MIT License \- see the [LICENSE.md](http://docs.google.com/LICENSE.md) file for details.