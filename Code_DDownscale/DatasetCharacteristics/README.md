# Dataset Characteristics

The code used to generate plots that shows Distribution of object size across different classes, helping visualize different opportutinies of downscale available for different query object class in different videos. The duration of video data is also plotted to show the extent of short video duration considered.

## Requirements
To compute the duration of video, the code requires that the datasets in question be downloaded and the corresponding (regenerated from frames and fps settings given in the dataset) videos be saved in the under appropriate folder given by variable VIDEO_ROOT_DIR. Also based on the dataset, the fps at which dataset was recorded is given by get_fps(dataset) function.

## Additional Meta Data generation
The distribution of GT object sizes for a given class in a video is visualized. The distribution visualized is set to be a set of 0th to 100th percentile object sizes, and is addtionally saved at ../BoundsEvaluation/intermediate_results/ , to be later used for evaluation of proposed methods.
