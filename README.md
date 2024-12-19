# spark-cursive-ocr

The task is to use OCR to transcribe handwritten cursive texts written in old English. 

Example 1 ~ 4 are example files provided by the client, Hampden County Registry of Deeds.

The initial attempt was to build my own OCR model. "OCR.ipynb" is the file for that. The results are in the folder "Tesseract OCR." It uses Tesseract to transcribe. I had to install poppler as well (it is in the zip file "Release-24.08.0-0.zip"). The results are okay in that it does transcribe, but not up the level of recognizable as actual English. 

For the next step, I decided to implement Azure's Document Intelligence. For keys, talk to Michelle about it. "AzureVision.py" is the file other team used for similar task of transcribing cursive from an image for other project. 
I wanted to see how the results would look like before building full code to automate, so I uploaded the files directly to Azure's Document Intelligence. The result is "document_intelligence_example1.txt." The results were not satisfying.

For the next step, I decied to try Google's Document AI. "DocumentAI" is the file I was working on until most recently. I haven't been able to figure out a way to use it yet. I'm assuming the issue is something to do with API key or permission level. Again, for the keys, talk to Michelle about it. 

If you have any questions, slack me (Woohyeon Her).