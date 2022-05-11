# Frame Annotation for Images
### Daniel Lee, Julie Song, Yichen Yao, Jung Ho Yoon
### Semantic Representation NLP - Daniel Bauer (Spring '22)

Our project, Frame Annotation for Images, can take a simple image in, and label that image with its frame semantic parsing. To do this, we take in an image and use the CNN-RNN Image Captioning model to caption that image; we then feed that caption into SLING, a framework that can parse semantic frames. Simultaneously, we run ImageAI’s object detector model on the input image to get all the objects and their positions. Then we run an NLTK word similarity algorithm to connect the image captions and semantic frames to the objects and their positions. Using this, we can output an image with labeled semantic frames.
