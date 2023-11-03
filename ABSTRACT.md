**Dark Face: Face Detection in Low Light Condition** is an object detection dataset containing 6100 images with 50399 labeled instances of a single class - *face*. It offers real-world low-light images taken at night in various locations like teaching buildings, streets, bridges, and parks. These images are labeled with bounding boxes highlighting human faces, serving as crucial *train* and *test* sets for accurate face detection in low light environments. Designed for [UG²+ Challenge Track 2](https://cvpr2022.ug2challenge.org/program21/dataset21_t2.html)

UG2+ Challenge Track 2 aims to evaluate and advance the robustness of object detection algorithms in specific poorvisibility situations, including challenging weather and lighting conditions. 

In Sub-challenge 2.2, authors use the self-curated Dark Face dataset. It is composed of 10,000 images (6,000 for training and validation, and 4,000 for testing) taken in under-exposure condition where human faces are annotated by human with bounding boxes; and 9,000 images taken with the same equipment in the similar environment without human annotations. 

<img width="408" alt="dark-face_preview_1" src="https://github.com/dataset-ninja/dark-face/assets/123257559/af0380ac-cd67-4f38-a23d-375c86f83824">

<span style="font-size: smaller; font-style: italic;">Sub-challenge 2.2: Dark Face has a high degree of variability in scale, pose, occlusion, appearance and illumination. The face regions in the red boxes are zoomed-in for better viewing.</span>

Additionally, authors provide a unique set of 789 paired lowlight/normal-light images captured in controllable real lighting conditions (but unnecessarily containing faces), which can be optionally used as parts of the training data. The training and evaluation set includes 43,849 annotated faces and the heldout test set includes 37,711 annotated faces. 

<i> Please Note, that test split consist of 100 images</i>
