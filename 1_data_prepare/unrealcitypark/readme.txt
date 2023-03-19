1a_generate_gt_custom_dots.py
generates custom binary ground truth dot maps with maximum dilation of 7 pixels and not touching nearest neighbor. 
By default output is in <datapath>/gt_map_custom2

There is no '1b_generate_gt_dotmap.py' for the City Park dataset. The dataset already contains dot maps in the '.npy' format. 
They are in the 'ground_truth_localization' folder


To run:
in main, set images_dir, mat_dir, out_dir for train and test datasets.