# blurring-image


How Cloud Functions Automate Image Blurring:

Trigger: A Cloud Function is activated when an image is uploaded to a specified Cloud Storage bucket.
Image Analysis: The function utilizes the Cloud Vision API to analyze the image for potentially offensive content, such as violence or adult content.

Blurring: If deemed offensive, the function employs an image processing library like ImageMagick to apply a blurring effect to the image, obscuring sensitive details.

Storage: The blurred image is then saved either to the same bucket or to a separate one for specific use cases.



Demo:
https://www.youtube.com/watch?v=jc7jnITxTcE
