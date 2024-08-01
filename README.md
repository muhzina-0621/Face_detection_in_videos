# Face Detection in Video with OpenCV

This project demonstrates how to use OpenCV to detect faces in a video and draw bounding boxes around them. The processed video is saved in the specified format (e.g., `.mp4`, `.avi`, `.mov`). This code is designed to run in Google Colab but can be adapted for local environments.

## Requirements

- Python 3.x
- OpenCV

## How to Use

### Step 1: Install Dependencies

Install the required Python packages. 

### Step 2: Upload Your Video

Upload the video file (e.g., `crowd.mp4`) to your working directory in Google Colab.

### Step 3: Run the Code

Run the code blocks sequentially in Google Colab to read the video, detect faces, draw bounding boxes, and save the processed video.

### Step 4: Download the Processed Video

After processing, the output video will be saved in your working directory. Download it to view the results.

## Output Format

The output video format can be adjusted by modifying the file extension and codec in the video writer setup.

## Notes

- This script uses the Haar Cascade classifier for face detection.
- Displaying video frames in Google Colab uses `cv2_imshow` instead of `cv2.imshow` due to limitations in the Colab environment.

The output video was unable to be uploaded due to file size.
