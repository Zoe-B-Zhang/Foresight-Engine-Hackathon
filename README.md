# Foresight-Engine-Hackathon
https://www.kaggle.com/competitions/banana/

# Foresight Engine: An AI-Powered Predictive Vision Tool

This project is a submission for the Kaggle Nano-Banana Hackathon. Foresight Engine uses Google's Gemini 1.5 Flash to analyze a time-series of images and generate a photorealistic prediction of a future state.

### How to Run

The entire project is contained within the `Foresight_Engine.ipynb` notebook.

1.  **Open in Google Colab:** Click the "Open in Colab" badge at the top of this README.
2.  **Set Up Your API Key:** The notebook requires a Google AI API Key. In Colab, go to the "Secrets" tab (key icon on the left) and add a new secret named `GOOGLE_API_KEY` with your key as the value.
3.  **Upload Example Images:** Create a folder in your Google Drive and upload the example image sequences (`images_bridge`, `images_plant`). Update the paths in the notebook's configuration area to point to your folders.
4.  **Run the Notebook:** Click "Runtime" -> "Run all". You can run all examples at once or use the interactive dropdown menu to select and run them individually.

### Technology Stack
* **Core AI Engine:** Google Gemini 1.5 Flash
* **Development Environment:** Google Colab
* **Core Libraries:** `google-generativeai`, `Pillow`, `Matplotlib`, `pathlib`
