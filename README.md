# Download

[[Google Drive]](https://drive.google.com/drive/folders/1MRtmqHhuC1FPPIl8IEkf7hawituoO37p?usp=sharing)

[[Baidu Drive]](https://pan.baidu.com/s/1PSyADEe4cIa0zxS2erQCfA?pwd=c2y1)

( To facilitate data exploration, we randomly sampled 5% of the data and stored it in the "M5HisDoc_examples" folder for reference. )

# License
The M<sup>5</sup>HisDoc dataset should be used and distributed under the [Creative Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) License](https://creativecommons.org/licenses/by-nc-nd/4.0/) for non-commercial research purposes.

# M<sup>5</sup>HisDoc Dataset
The M<sup>5</sup>HisDoc dataset comprises a collection of 8,000 images, 403,824 text lines with 4,367,392 characters in 16,151 categories. 

M<sup>5</sup> indicates five properties of style, ie., Multiple layouts, Multiple document types, Multiple calligraphy styles, Multiple backgrounds and Multiple challenges. The M<sup>5</sup>HisDoc dataset consists of two subsets, M<sup>5</sup>HisDoc-R (Regular) and M<sup>5</sup>HisDoc-H (Hard). The M<sup>5</sup>HisDoc-R subset comprises 4,000 historical document images. To ensure high-quality annotations, we meticulously perform manual annotation and triple-checking. To replicate real-world conditions for historical document analysis applications, we incorporate image rotation, distortion, and resolution reduction into M<sup>5</sup>HisDoc-R subset to form an new challenging subset named M<sup>5</sup>HisDoc-H, which contains the same number of images as M<sup>5</sup>HisDoc-R.


Both the annotations in character-level and text-line-level are provided, including text bounding box, text content, and the corresponding reading order. Therefore, M<sup>5</sup>HisDoc can be applied on a wide range of tasks, including text-line/charater detection, recognition and reading order prediction.


# Directory Format
The dataset is organized in the following directory format:
```
├── M5HisDoc
    ├── M5HisDoc_regular
        ├── images
        │   ├── xxx.jpg
        │   └── ...
        ├── label_textline
        │   ├── xxx.txt
        │   └── ...
        ├── label_char
        │   ├── xxx.txt
        │   └── ...
    ├── M5HisDoc_hard
        ├── images
        │   ├── xxx.jpg
        │   └── ...
        ├── label_textline
        │   ├── xxx.txt
        │   └── ...
        ├── label_char
        │   ├── xxx.txt
        │   └── ...
    ├── split_train.txt
    ├── split_val.txt
    ├── split_test.txt
    ├── char_dict.txt


```

# Contact
For any questions about the dataset, please contact the authors by sending an email to Prof. Jin([eelwjin@scut.edu.cn](mailto:eelwjin@scut.edu.cn), or [lianwen.jin@gmail.com](mailto:lianwen.jin@gmail.com)). 
