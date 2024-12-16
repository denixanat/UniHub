# **University News Website**  

## **Overview**  
This project is a web-based application designed to list and display news articles from two universities. It includes functionalities for translation, filtering, and searching articles, enhancing accessibility and user experience.  

---

## **Features**  

1. **News Article Management**  
   - News articles are stored in a JavaScript file as a constant array in JSON format, simplifying data management and separation from HTML and JavaScript logic.  
   - Articles include properties like author, title, content, tags, and university affiliation for dynamic interaction.  

2. **Language Translation**  
   - Utilizes the **Google Cloud Translation API** to support English and Spanish.  
   - Default language matches the article's original language.  
   - A toggle button allows users to switch between English and Spanish while preserving articles in their respective languages.  

3. **Filtering Functionality**  
   - Users can filter news based on:  
     - **Categories** (tags).  
     - **University affiliation**.  
   - This feature ensures that users view only the articles most relevant to their interests.  

4. **Search Functionality**  
   - Users can search for articles containing specific keywords or terms.  
   - Search results dynamically match the input text with article content.  
   - Search can be combined with filtering for precise results.  

5. **Responsive Design**  
   - Leverages **Bootstrap** for design and responsiveness, ensuring compatibility across devices and screen sizes.  

---

## **Structure**  

- **HTML Pages**:  
  1. **Main Page**: Lists all news articles with default filters and search options.  
  2. **Category Page**: Displays filtered articles based on user selection.  
  3. **Article Page**: Shows detailed content of a selected article, with translation options.  

- **JavaScript File**:  
  - Contains the constant array with all articles in JSON format.  
  - Provides dynamic functionality for filtering, searching, and translation.  

---

## **Technical Details**  

1. **Translation**  
   - Implements the Google Cloud Translation API to ensure seamless bilingual support.  
   - Button toggles between English and Spanish for all visible articles.  

2. **Filtering and Searching**  
   - Articles are filtered by **tags** and **university affiliation** properties.  
   - Search matches keywords with article content, title, and tags.  

3. **Design**  
   - Bootstrap is used for styling, enhancing user interface and cross-device compatibility.  

---

## **Setup and Usage**  

1. Clone the repository and open the main HTML file in a browser.  
2. Ensure the JavaScript file is included as a script in all HTML pages.  
3. Enable the Google Cloud Translation API key to activate translation functionality.  

Enjoy exploring news articles seamlessly in English and Spanish!  
