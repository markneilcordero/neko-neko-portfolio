### **Neko Neko Portfolio Documentation**

---

### **Welcome!**  
The **Neko Neko Portfolio** is a simple, stylish portfolio website designed to showcase photography work. It features a paginated image gallery, smooth navigation, and a contact form for potential clients to get in touch.

---

### **Features**  
- **Dynamic Image Gallery:** A grid layout that displays images with pagination (10 images per page).  
- **Randomized Order:** Images are randomized each time the page is loaded.  
- **Modal Image Viewer:** Clicking on an image opens it in a modal for a larger view.  
- **Responsive Design:** The layout adapts for desktop and mobile screens.  
- **Contact Form:** A simple form to collect the user’s name, email, and message.

---

### **How to Use**  
1. **Homepage Navigation:**  
   - Use the navigation links (`Home`, `Portfolio`, `Contact`) to jump to different sections of the page.

2. **Portfolio Section:**  
   - Click the **Portfolio** link or scroll down to see the image gallery.
   - Click on any image to view it in a **modal popup**.
   - Use the pagination buttons to browse more images.

3. **Contact Section:**  
   - Fill out the form with your details (name, email, and message).
   - Click **Send** to submit your message.

---

### **Technical Details**  
- **Fonts:**  
  - Custom font `nekoneko` (Oriental Cats) is used for text.  
- **Pagination:**  
  - Powered by **pagination.js** to display 10 images per page.  
- **Modal:**  
  - **jQuery Modal** is used to display images in a fullscreen modal window.  
- **Image Source:**  
  - Images are sourced from the `images/portfolio/` folder (`image1.webp` to `image61.webp`).

---

### **Dependencies**  
- `jquery-3.7.1.js`: For DOM manipulation.  
- `pagination.min.js`: For paginating the image gallery.  
- `jquery.modal.js` and `jquery.modal.css`: For creating modal windows.

---

### **File Structure**  
```bash
.
├── index.html          # Main HTML file
├── assets/             
│   ├── output.css      # Custom Tailwind CSS styling
│   ├── pagination.css  # Pagination styles
│   ├── pagination.min.js  # Pagination functionality
│   ├── jquery-3.7.1.js # jQuery library
│   ├── jquery.modal.js # Modal script
│   └── jquery.modal.css # Modal styling
├── images/
│   └── portfolio/      # Image files (image1.webp to image61.webp)
└── fonts/
    └── OrientalCatsLight-2OzB8.otf  # Custom font
```

---

### **Sample Flow**  
1. The page loads and displays the **header** with a **Neko Neko Photographer** introduction.
2. The **Portfolio** section shows the first 10 images, with pagination below.
3. Click an image to open it in a **modal viewer**.
4. Scroll down to the **Contact** form to send a message.

---

### **How to Run the Project**  
1. Clone or download the project files.  
2. Open `index.html` in your browser.  
3. Ensure the `assets/`, `images/`, and `fonts/` folders are in the same directory as `index.html`.

---

This portfolio is a great way to display photography work in an elegant and functional layout.
