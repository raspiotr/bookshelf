### Bookshelf (HTML+CSS+JavaScript)

---

### Header:

- **Mobile:**
  - Logo, theme switcher, and hamburger menu with navigation (Home, Shopping list).
- **Tablet & Desktop:**
  - Logo, navigation (Home, Shopping list), and theme switcher.
- **Clicking the logo or Home opens the Home page.**
- **Clicking Shopping list opens the page with a list of books added to the cart.**
- **Clicking the theme switcher changes the current site theme to another (dark or light).**
- **Clicking the hamburger menu expands it to the full height of the viewport.**

### Home:

- **A block with a list of all book categories.**
- **A block with a list of charity foundations in the form of a vertical slider.**
- **A block with a list of books belonging to all categories or to a specific category.**
- **When navigating to the Home page, the book list block displays popular books divided into categories. If no such books are found, the user should be displayed an appropriate message.**
- **Design a card template for a single book.**
- **Clicking any category should display the books belonging to that category in the book list block. If no such books are found, the user should be displayed a message.**
- **Clicking the logo of any charity foundation should open its original resource in a separate browser tab. Charity foundation table =>.**
- **Clicking the See more button assigned to each category should display the books belonging to that category in the book list block. If no such books are found, the user should be displayed a message.**
- **Clicking any book should open a modal window with detailed information about it.**

### Modal Window:

- **The modal window with detailed information about the book contains:**
    - Cover image of the book.
    - Title of the book.
    - Author of the book.
    - A short description of the book's content.
    - A list of links to e-commerce platforms where the book can be purchased.
    - A button to add or remove the book from the shopping list.
- **Clicking on the logo of the e-commerce platform should open its original resource in a separate browser tab, where the user can purchase the book.**
- **Clicking the button to add or remove the book from the shopping list should update the list information, which should be stored in localStorage.**
- **Clicking the modal window background, the button with the cross icon, or pressing the ESC key should close the modal window (don't forget to remove the event listeners).**

### Shopping List:

- **A block with a list of charity foundations in the form of a vertical slider (desktop version).**
- **A block with a list of books added by the user to the shopping list.**
- **When navigating to the Shopping list page, the book list block displays the books added to it by the user and saved in localStorage. If no such books are found, the user should be displayed a message.**
- **Design a single book card template. The book card contains:**
    - Cover image of the book.
    - Title of the book.
    - Category of the book.
    - A short description of the book's content.
    - Author of the book.
    - A list of links to e-commerce platforms where the book can be purchased.
    - A button to remove it from the shopping list.
