# Dataset Characteristics

The code used to generate plots that shows Distribution of object size across different classes, helping visualize different opportutinies of downscale available for different query object class in different videos. The duration of video data is also plotted to show the extent of short video duration considered.

## Some Code Insights
### Requirements
To compute the duration of video, the code requires that the datasets in question be downloaded and the corresponding (regenerated from frames and fps settings given in the dataset) videos be saved in the under appropriate folder given by variable VIDEO_ROOT_DIR. Also based on the dataset, the fps at which dataset was recorded is given by get_fps(dataset) function.

### Additional Meta Data Generation
The distributions of GT object sizes for selected classes in a video are visualized. The distribution visualized is set of object sizes from 0th to 100th percentile (at a gap of 1), and is addtionally saved at ../BoundsEvaluation/intermediate_results/ , to be later used for evaluation of proposed methods.
