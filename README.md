# Document Processing Tool - Search Engine

## Project Overview

This project is a real-world application of data structures concepts. It operates similarly to a search engine, returning all matching sentences from the provided corpus based on the user's query. The system is capable of handling queries that may start or end in the middle of words, ensuring that all relevant results are retrieved.

### Key Features

- **Custom Dictionary Implementation:** Keeps track of word occurrences across the corpus.
- **Efficient Search:** Returns sentences matching the user's input query, regardless of word boundaries.
- **Data Structures:** Uses custom data structures for efficient storage and retrieval of information.

## Tech Stack

- **Programming Language:** C++
  - C++ was chosen for its efficiency and control over system resources, which are critical for handling large datasets in real-time.
  
- **Core Libraries:**
  - `dict.h`: Custom header file that defines and manages the dictionary structure used for counting word occurrences and storing sentences.

- **Data Structures:**
  - **Symbol Table:** A custom data structure used for storing and retrieving words and their occurrences efficiently.
  - **SymNode:** A node structure used in the Symbol Table to represent each word and its frequency.

- **File Handling:**
  - The system can dump the contents of the dictionary to a file for further analysis or persistence, using the `dump_dictionary` method.

