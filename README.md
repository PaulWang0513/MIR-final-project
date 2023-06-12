# MIR final project
- This is the final project of team 找房大隊 in course NTHU11120CS573100
> Author: NTHUCS23級 王鴻昱、黃子瑋、黃冠維

## Directory structure
- `data/`: The directory to store the training data and testing data, including the audio files and the corresponding labels.
    - `audio/`: The directory to store the audio files. Two audio files with different noise added on the original audio are included in the directory.
    - `label/`: The directory to store the labels of the audio files.
- `demo/`: The directory to store the demo files.
    - `output/`: The directory to store the output files of the demo.
- `model/`: The directory to store the trained model. Two models are provided (SVM and MLP) in the directory.

## Quick Run
- Just run the final_project.ipynb in the root directory.
- By default, it will load two trained models, process all audio in the `demo/` directory, and output the results to the `demo/output/` directory.