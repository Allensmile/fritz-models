# Fritz Models
A collection of machine and deep learning models designed to run on mobile devices.

Models in this repository contain code and utility for training models as well as converting them to mobile-friendly formats like Core ML, TensorFlow Mobile, and TensorFlow Lite.

## Models

* [Image Labeling](image_labeling/): Label images based on their content.
* [Object Detection](object_detection/): Localize and label objects in an image with a bounding box.
* [Style Transfer](style_transfer/): Transform images into works of art by transfering the style of one image onto the content of another.
* [Image Segmentation](image_segmentation/): Semantic segmentation of images. Assign a value to each pixel of an image corresponding to the type of object it belongs to.
* [Create ML Playgrounds](create_ml_playgrounds/): A series of playgrounds for training models with Apple's Create ML tool

Don't see the model you're looking for? Open an issue and let us know!

## Add to your app
To see live demonstrations of these models running on-device, the Heartbeat App is available in both the [App Store](https://itunes.apple.com/us/app/heartbeat-by-fritz/id1325206416?mt=8) ([source code](https://github.com/fritzlabs/heartbeat-ios)) and [Play Store](https://play.google.com/store/apps/details?id=ai.fritz.heartbeat) ([source code](https://github.com/fritzlabs/heartbeat-android)).

If you'd like to incorporate any of these models or versions you've trained into your own app, head over to [Fritz](https://fritz.ai/?utm_source=github&utm_campaign=fritz-models). SDKs are available for both iOS and Android.

## Additional resources

Additional, [non-code resources](resources/README.md) for machine learning and AI.

* [AI and ML Landscape](resources/AI_Landscape.md): our curated list of helpful products and services for AI and machine learning.
* [AI and ML Newsletters](resources/AI_ML_Newsletters.md): a list of relevant newsletters in AI and machine learning.
* [Facebook Groups for AI/ML, Mobile, and Data Science](resources/AI_ML_Mobile_Facebook_Groups.md): A list of AI/ML, mobile dev, and data science Facebook communities.

## Join the community
[Heartbeat](https://heartbeat.fritz.ai/?utm_source=github&utm_campaign=fritz-models) is a community of developers interested in the intesection of mobile and machine learning. [Chat with us in Slack](https://join.slack.com/t/heartbeat-by-fritz/shared_invite/enQtMzY5OTM1MzgyODIzLTZhNTFjYmRiODU0NjZjNjJlOGRjYzI2OTIwY2M4YTBiNjM1ODU1ZmU3Y2Q2MmMzMmI2ZTIzZjQ1ZWI3NzBkZGU) and stay up to date on the latest mobile ML news with our [Newsletter](https://mobileml.us16.list-manage.com/subscribe?u=de53bead690affb8e9a21de8f&id=68acb5c0fd).

## A note about large files
Large files like model checkpoints, data, and archives of compiled code are managed via `git lfs`. You need to have Git LFS installed in order to download these files. Installation instructions are available [here](https://github.com/git-lfs/git-lfs#getting-started).

If you have Git LFS installed, large files will download automatically by default. This can take a while and require a good connection. To clone this repository without downloading the model checkpoints, you can run:

```
GIT_LFS_SKIP_SMUDGE=1 git clone ...
```
