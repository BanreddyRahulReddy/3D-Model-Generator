
# 3D Model Generator

## Project Overview
This Jupyter Notebook takes user input in the form of a **photo** or a **text description** and generates a basic 3D model. It uses:
- A cube as a placeholder 3D model for **photo input**
- A sphere as a placeholder 3D model for **text input**

This notebook demonstrates basic 3D shape creation and visualization using the `trimesh` library, along with simple image loading using `Pillow`.

## Requirements

Make sure to install the required Python libraries before running the notebook:
```bash
  pip install pillow trimesh
```

## How to Run the Notebook
Open your terminal or Anaconda Prompt.

Navigate to the folder containing the notebook:

```bash
  3d_model_generator.ipynb
```

Launch Jupyter Notebook:

```bash
  Jupyter Notebook
```

Open the file named 3d_model_generator.ipynb.

Run all the cells in order.

## Usage Instructions
1. Run the Jupyter Notebook `3d_model_generator.ipynb`.
2. You'll be prompted in the output cell:
3. Type `text` or `photo` based on your preferred input type:
- For example: `text`
4. If you chose `text`, you’ll be prompted:
- For example: `a toy dinosaur`
5. The program will:
- Print: `Text received: a toy dinosaur`
- Save the 3D model
- Show: `Model saved successfully.`
- Display the 3D shape (a sphere in this case)

## My thought Process
I wanted to make a program that can take either a photo or a short text and turn it into a basic 3D shape. So, I first asked the user what kind of input they want to give. If they chose "photo", I asked for the image file name and created a cube shape as a placeholder model. If they chose "text", I took their description and created a sphere shape instead. If they entered something wrong, I just showed an error message.

Once the shape was made, I saved it as a .stl file. If no model was created, I just printed a message saying that. 

