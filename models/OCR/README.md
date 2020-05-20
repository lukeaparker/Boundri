## Scope:
- Beginning with just OCR with the goal of transcribing text from a photograph of the real world into digital text
- Only text recognition of letters and numbers in English will be considered at first
- Would like to transcribe entire sentences / paragraphs of text or just individual words
- Should use a pre-trained model
- Text should be clearly visible, in focus, and typed in a large readable printed font

## Function: transcribe_text(image)
Input:
RGB image data from 720p photograph (could be an image object from any library, this may change for efficiency  purposes depending on the API / model used) Photograph will either contain no text, a single world, one sentence, or a small paragraph

Output:
String of predicted text from the image
Performance:
Metric: % of words accurately predicted
Goal: 50% word prediction accuracy

## Tasks
By Friday, May 22, Tanner and Ryan will: 
Research different pre trained models. Select several models to work on and collaborate to ensure they are not working on the same model
By Sunday, June 7, Tanner and Ryan will:
Implement selected models in Python
Collect and combine datasets containing equal numbers of photographs that will either contain no text, a single world, one sentence, or a small paragraph
Evaluate model performance based on prediction accuracy on the combined dataset 
Lastly, the model with the best performance will be selected for use in this project and the others will be archived
