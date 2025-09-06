# PetSeek

**PetSeek** is a smart image search engine for adoptable animals. It allows users to find relevant pet images by typing natural language queries.(e.g: black bulldog, white golden retriever).

---

## Features
- Supports multiple pet categories: dogs, cats, turtles, rabbits, birds...
- Uses OpenAI's **CLIP** model to understand text-image similarity
- Powered by **FAISS** for fast image indexing and retrieval
- Matches results based on semantic meaning, not just filenames(cosine similarity).

---

## Technologies Used

- Python
- CLIP (Contrastive Language–Image Pretraining)
- FAISS (Facebook AI Similarity Search)
- NumPy, PIL, and other helper libraries

---

## How to Run

### Run in Google Colab (No installation needed)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yasmine-Hmida/PetSeek-SearchEngine/blob/main/PetSeek.ipynb)

1. Click the **"Open in Colab"** button above.
2. Make sure to enable a GPU from **Runtime > Change runtime type > GPU**.
3. Copy the **ImageSearch** folder into your Google Drive, directly under **My Drive**.
- The folder structure should look like: <br>
````
My Drive/ 
 └─ ImageSearch/ 
      ├─ whiteBulldog1.jpg 
      ├─ turtle1.jpg 
      └─ ...
````
4. Run each cell in order to launch PetSeek.
- The notebook automatically uses the folder path **/content/drive/MyDrive/ImageSearch**.
- No path changes are needed if the folder is placed correctly.
