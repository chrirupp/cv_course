# Notebooks for the CV Course, MM 2026, Christian Rupprecht

Instructions for running the notebooks of each lecture on Google Colab.

1. Start Google Colab: https://colab.research.google.com. A modal dialog should have appeared to open a new notebook. If not, go to "File>Open notebook".
2. From the open notebook dialog, select the GitHub "tab" and enter this URL: https://github.com/chrirupp/cv_course
3. The notebook(s) should appear (*.ipynb). Select the one for the current lecture.
4. [If GPU acceleration is necessary] Go to "Edit > Notebook settings" and select "GPU" for Hardware accelerator. Changing this later requires restarting the runtime which will loses previous results and requires downloading the data files again.
5. To run a notebook on Colab you will typically need some data files (e.g., images). As Colab only loads the notebook itself, these other files need to be downloaded separately. The second cell is a `%%sh` block that downloads the required files. You can inspect the downloaded files by clicking on the "Files" tab on the left.

## Lecture notebooks

Each lecture comes with a notebook that produces the examples shown on the slides. Notebooks marked GPU load large pretrained models and are much faster with a GPU runtime.

| Lecture | Notebook | Contents |
|---|---|---|
| 2 Filtering | `02_ImageEnhancement.ipynb` | colour channels, sampling, point-wise and geometric transformations, linear and non-linear filters |
| 3 Fourier | `03_Fourier.ipynb` | DFT, basis functions, spectra of images, filtering in the frequency domain |
| 4 Restoration | `04_Restoration.ipynb` | degradations, inverse filtering, Wiener filter, an inverse problem with a prior |
| 5 Matching | `05_MatchingIndexSearch.ipynb` | SIFT keypoints and matches, bag of visual words, homography warping, LoG |
| 6 Classification | `06_classification.ipynb` | CIFAR-10, nearest neighbours, decision boundaries of k-NN and a linear SVM, softmax temperature |
| 7 CNNs | `07_cnns.ipynb` | convolution as a filter bank, feature maps of a ResNet, pooling, effective receptive fields |
| 8 Transformers | `08_transformers.ipynb` | attention as a soft lookup, patch tokens, learned positional embeddings, attention distance, normalisation layers |
| 9 Visualisation | `09_visualisation.ipynb` | filters, embeddings (PCA, t-SNE), occlusion, gradients, input maximisation, ViT attention (GPU) |
| 10 Detection | `10_detection.ipynb` | HOG, selective search, R-CNN style classification, Faster R-CNN with and without NMS, RPN proposals, DETR (GPU) |
| 11 Segmentation | `11_segmentation.ipynb` | semantic segmentation, checkerboard artefacts, Mask R-CNN, human pose, SAM (GPU) |
| 12 Video | `12_video.ipynb` | frame differences, optical flow (Farnebäck vs. RAFT), 3D CNN filters, cost of space-time attention (GPU) |
| 13 Tracking | `13_tracking.ipynb` | Lucas-Kanade from scratch, aperture problem, KLT vs. CoTracker3 with occlusions (GPU) |
| 14 Camera models | `14_camera_models.ipynb` | pinhole vs. orthographic, dolly zoom, vanishing points, calibration (DLT and non-linear) |
| 15 Multiple view geometry | `15_mvg.ipynb` | plane and parallax, epipolar lines, eight-point algorithm, degenerate configurations, triangulation |
| 16 Generative models | `16_generative.ipynb` | ODEs and Euler's method, 2D flow matching |
| 17 Representation learning | `17_representation_learning.ipynb` | DINOv2 features and correspondences, CLIP vs. SigLIP, typographic attacks (GPU) |
| 18 3D and world models | `18_3d_world_models.ipynb` | monocular metric depth, lifting an image to 3D, novel views and their holes (GPU) |
| 19 Vision and language | `19_vision_language.ipynb` | tokenisation, visual tokens, a small VLM and its hallucinations (GPU) |
