
# Classification of Eye Diseases using Artificial Intelligence

Short description
This project began as my B.Sc. thesis at KNTU in collaboration with Negah Hospital. The original focus was on classifying Dry and Wet Age-related Macular Degeneration (AMD) against normal eyes (3 classes) using deep learning on a small local dataset. The model reached ~92% accuracy on the small dataset (285 images) without overfitting using transfer learning on pretrained networks.
Later this project was expanded for a conference presentation in the 33th ISME (Iranian Society of Mechanical Engineers) conference in Iran. 
We are currently working to submit this as a journal paper. It has changed significantly. The number of photos has been increased to 9000 from 119 patients and Diabetic Retinopathy was added as another class due to the importance of early detection in these cases.

Collaborators
- Negah Hospital (clinical collaborator)
- Co-author: Mostafa Amiri
- Superviser: Mahkameh Sharbatdar (Asistant professor at KNTU university)

Repository structure (recommended)
- README.md (this file)
- data/
  - README.md (data description, usage policy)
  - raw/ (if permitted)
  - processed/
- notebooks/
  - 01-data-exploration.ipynb
  - 02-training.ipynb
  - 03-evaluation.ipynb
- src/
  - data_utils.py
  - model.py
  - train.py
  - evaluate.py
- models/
  - best_model.pth
- assets/
  - screenshot1.png
  - confusion_matrix.png
- slides/
  - ISME_presentation.pdf
  - ISME_presentation.pptx
- docs/
  - paper_draft.pdf
  - ethics-and-data-access.md



Contact
Parsa Aghaei — your.email@example.com
