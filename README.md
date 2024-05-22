create a .env file and add this:
HUGGINGFACEHUB_API_TOKEN = XXXXXXXXXXXXXXXXXXX (the actual key)

you can find a hugging face key on your hugging face account. 

run the python files in the terminal: python textToImage.py

imageToText saves its output to output.txt.
The image will be saved to image.jpg(and overwrite any image that's already saved)

textGeneration and textToImage take their prompt from output.txt

textToImage saves the generated image to image.jpg(and overwrite any image that's already saved)

textGeneration saves its output to textGenerationOutput.txt
