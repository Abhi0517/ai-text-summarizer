# AI-Text Summarizer
A web-application designed to simplify and summarize your texts! This app leverages the power of Artificial Intelligence APIs to provide concise summaries of long texts, whether you have a lengthy artice or a research paper. It leverages the Hugging Face Inference API with Facebook’s bart-large-cnn model for generating accurate summaries, built with NodeJS and Express on the backend and a user interface using HTML, CSS, and JavaScript.

## WorkFlow and Execution
* Either clone this repository or import it to Replit(Click the *Run* button to start the project).
  
  <img width="1910" height="902" alt="Screenshot 2025-09-03 142326" src="https://github.com/user-attachments/assets/bb7101b9-44d4-4a94-bf67-effb12ef71b5" />

* Postman interface was utilized to test APIs and modify the code.
  
  <img width="1770" height="876" alt="Screenshot 2025-09-03 100448" src="https://github.com/user-attachments/assets/deaa936f-282a-4636-8354-5d9ddc182367" />

* Consider the following example test case:

  <img width="1919" height="915" alt="Screenshot 2025-09-03 122911" src="https://github.com/user-attachments/assets/6f27b402-4b09-480c-8386-96a150e7b53c" />

## Tech Stack
Tools and technologies used:
* Front end:
  * HTML
  * CSS
  * JavaScript

* Back end:
  * Node.js
  * Express
  * Hugging Face Inference API

* API platform:
  * Postman

* Code Editor/Deployment tool:
  * Replit

## Points to Consider
* The API call in Postman is a POST request to the endpoint https://api-inference.huggingface.co/models/facebook/bart-large-cnn with a body containing JSON data. The request's body includes the text to summarize and parameters specifying the minimum and maximum length of the summary.
* Before proceeding with the project, you need to signup to https://huggingface.co and create an *Access Token* there.
* Then that *Access Token* is to be added in a *.env* file(create new) or as a *Secret* in *Replit*.
* Nothing else, the project will now be ready to build.

## Sample Text
    In the enchanted forest of Eldoria, two unlikely friends, Lyra and Fenris, found themselves at a crossroads. Lyra was a young elf, her skin the color of birch bark and her hair a cascade of moonlight silver. She possessed the rare gift of communicating with the ancient trees, listening to their whispers and deciphering their secrets. Fenris, on the other hand, was a gruff but loyal dwarf, his beard a tangle of fiery red and his hands calloused from years of working with stone and metal. His strength was unmatched, and his knowledge of the underground tunnels and forgotten mines was invaluable.

## Feel free to fork and contribute !!

