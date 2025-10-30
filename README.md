# book
using react created book searching 
using titles and book names we can find book online used react and js css

Imports=>React: Library for UI building. useState: Hook for managing state.  App.css: Custom styling file.

useState Hooks=>query: Stores the user input. - books: Stores book data from API. - loading: Shows spinner when loading. - searchType: Search filter (title, author,)

searchBooks Function=> Checks if input is empty. - Fetches data from Open Library API. - Converts data to JSON. - Updates 'books' state. - Stops spinner after loading.

Search Section=>Includes dropdown (type), input box, and Search button.

Books Display Section=> Loops through book list and displays: • Cover image • Title and author • Link to Open Library page

Footer=> Dark bar at the bottom with © 2025 Book Finder text.

CSS Styling=>- Ensures full height layout. - Fixes footer at bottom. - Adds padding and background color. result=> Built with React + css Uses Open Library API ■ Features: Search, Spinner, Cards, Sticky Foot
