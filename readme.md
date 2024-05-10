This dataset comprises three distinct sunflower meal (SFM) samples, each characterized by varying levels of crude protein. For each sample, 70 high-resolution photographs (6,000 x 8,000 pixels) were captured using a 48-megapixel camera. The images were taken from multiple angles under controlled lighting to maintain uniform image quality and reduce variability. Each sample was positioned against a consistent white background, enhancing the ease of image segmentation and feature extraction. During the photo sessions, careful attention was given to keep a uniform distance and angle between the camera and the samples.

Following the photo capture, several image processing steps were undertaken to extract numerical features suitable for machine learning analysis. The process began by selecting the largest square region from the raw images, ensuring the sunflower meal was the sole focus and the white background was excluded. A 224x224 pixel window was then defined starting from the top-left corner of this square, and the contents within this window were captured. Additionally, three variants of each image were created by rotating the original image 90 degrees clockwise. By shifting this window within the designated 224x224 pixel area, data was systematically generated for use in classification models. Utilizing this methodology, a total of 5,100 images were produced, with each of the three classes contributing 1,700 images, derived from 210 original photographs.
