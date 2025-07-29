# CMMI_Coding_Assignment

This repo contains Kaggle notebook for Coding Assignment "Stereo‑Vision Boat Detection, Depth Estimation & Geo‑Tracking"

In addition it contains:
- Folder Task_3_1_output with two json files: `detections_cam_North.json` and `detections_cam_South.json`
- Folder Task_3_2_output with  movie `perception_stack_output.mp4`. Since json files are quite big, here are google-drive links to them:
depths_cam_South.json: https://drive.google.com/file/d/1DcPn5O1kynB_oCkD6i8Q89P_P5OE48GC/view?usp=sharing

depths_cam_North.json: https://drive.google.com/file/d/1kBP933MP6CZ7bBiIG33kACbPtvwK3CI2/view?usp=sharing
  
- File `Report.pdf` with description of all steps
- File Validation_dataset_200images.zip with 200 annotated images
- File Validation_dataset_55images.zip with 55 annotated images
- File `detection-task-cmmi_Kaggle.ipynb` - Kaggle notebook for assignment

Notebook is prepared to run on Kaggle platform. Here are the main steps:

1. Go to "File", then "Import notebook" and select "CMMI_assignment.ipynb"
2. Go to "Settings" and then to the "Accelerator" and select "GPU P100"
3. You need to upload the assignment data:
   
 3.1 Go to Sidebar, then expand "Input" and click "Upload", then choose "Assignment_Data_Coding_Exercise_06_2025.zip"
 
 3.2 Put the name for the assignment data: "/kaggle/input/marina-stereo-vision-vessel-images-full/assignment_data", 
  thus the path for the assignment data must be: "/kaggle/input/marina-stereo-vision-vessel-images-full"
  
4. You need to upload the small validaton dataset:

 4.1 Go to Sidebar, "Input" and click "Upload", then choose "Validation_dataset_55images.zip"
 
 4.2 Put the name for the validation data: "marina-validation", 
  thus the path for the assignment data must be: "/kaggle/input/marina-validation"
  
5. You need to upload the full validaton dataset:
   
 5.1 Go to Sidebar, "Input" and click "Upload", then choose "Validation_dataset_200images.zip"
 
 5.2 Put the name for the validation data: "marina-validation-200", 
  thus the path for the assignment data must be: "/kaggle/input/marina-validation-200"

6. Run cells from top, one to one
 
