# dev_manual_clean_shorelines

This program aims to perform a manual clean of detected coastlines, to only keep clean parts of detections.

Arguments of the program:
- Input_dir_coastlines
- Output_dir (selected coastlines)
- Images_dir (Directory containing average images 'A_CAM*fps_*s_*.jpg')

During execution, the user will have the following choices to process the shoreline:
- Keep the shoreline as it is (if lucky !)  -> option 'k'
- Throw away the shoreline (dirty case)     -> option 't'
- Remove any part(s) of the shoreline         -> option 'r'
- Choose any part(s) of the shoreline         -> option 'c'


