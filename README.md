## How to run the program:
- Clone and extract the repository. 
- Open terminal in the directory inside the extracted folder the extracted.
- To run the detector on a video file, run the following line on the terminal:
    ```sh
    python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat --video <file_name>
    ```
    where *<file_name>* is the video file's path. For example:
    ```sh
    python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat --video video.mp4
    ```
- To run the detector on a video stream from web camera, run the following line on the terminal:
    ```sh
    python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat
    ```