# virtual_eye

PYTHON 3.8
---------------------------------------------

### Description:
This project is used to apply photoshop filters to IRIS eye and create a virtual eye from it.

### Example1
![Screenshot from 2023-10-01 20-48-39](https://github.com/Dimensions-Limited/virtual_eye/assets/68796875/e02cb2a6-a36f-47dc-bdf8-c8666c58f604)

### Example2

![Screenshot from 2023-10-01 20-54-02](https://github.com/Dimensions-Limited/virtual_eye/assets/68796875/ba45590f-4a19-4efe-8514-1886638b4156)



### Installation

```BibTeX
git clone git@github.com:shkhamza143/virtual_eye.git
cd virtal_eye
git clone https://github.com/facebookresearch/detectron2.git
cd detectron2
python -m pip install -e .
cd ..
pip install -r requirements.txt
```


### Model Zoo
Download the model from [Google Drive]()

## Getting Started

Run the Following Script
```BibTeX
python inference.py -s <source images> -t <target_images_list>
```

## TODO
- Add training script for detectron2


## Citing Detectron2

If you use virtual eye in your research or wish to refer to the baseline results published in the [Google Drive](), please use the following BibTeX entry.

```BibTeX
@misc{wu2019detectron2,
  author =       {Hamza Naeem},
  title =        {virtual eye},
  howpublished = {\url{https://github.com/Dimensions-Limited/virtual_eye}},
  year =         {2023}
}
```
