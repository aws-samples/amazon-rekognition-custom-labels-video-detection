## Amazon Rekognition Custom Labels - Video Object Detection

Developing a custom model to analyze images is a significant undertaking that requires time expertise, and resources, often taking months to complete. Additionally, it often requires thousands or tens-of-thousands of hand-labeled images to provide the model with enough data to accurately make decisions. 

Amazon Rekognition Custom Labels takes care of the heavy lifting for you when creating your custom model. The service includes automated machine learning (AutoML) capabilities that take care of the machine learning for you. When the training images are provided, Amazon Rekognition Custom Labels can automatically load and inspect the data, select the right machine learning algorithms, train a model, and provide model performance metrics.

Once the model is trained, your can start making inferences to detect custom labels in your images. When working with videos, currently, we need to extract the frames and call the service to make the inference. In the notebook located in this repository you will learn how to extract the images from a video, call your custom model, draw bounding boxes over the frames and reconstruct the video.

**To use the notebook in this repository you need to have previously trained a model with Amazon Rekognition Custom Labels**

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

