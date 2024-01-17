# Notebooks for the CV Course, HT 2024, Christian Rupprecht

Instructions for running the notebooks of each lecture on Google Colab.

1. Start Google Colab: https://colab.research.google.com. A modal dialog should have appeared to open a new notebook. If not, go to "File>Open notebook".
2. From the open notebook dialog, select the GitHub "tab" and enter this URL: https://github.com/chrirupp/cv_course
3. The notebook(s) should appear (*.ipynb). Select the one for the current lecture.
4. [If GPU acceleration is necessary] Go to "Edit > Notebook settings" and select "GPU" for Hardware accelerator. Changing this later requires restarting the runtime which will loses previous results and requires downloading the data files again.
5. To run a notebook on Colab you will typically need some data files (e.g., images). As Colab only loads the notebook itself, these other files need to be downloaded separately. The second cell is a `%%sh` block that downloads the required files. You can inspect the downloaded files by clicking on the "Files" tab on the left.