# FlowQA

This is our first attempt to make state-of-the-art single-turn QA models conversational.
Feel free to build on top of our code to build an even stronger conversational QA model.

For more details, please see: [FlowQA: Grasping Flow in History for Conversational Machine Comprehension](https://arxiv.org/abs/1810.06683)

#### Step 1:
perform the following:
```shell
pip install -r requirements.txt
```
to install all dependent python packages.

#### Step 2:
download necessary files using:
```shell
./download.sh
```

#### Step 3:
preprocess the data files using:
```shell
python preprocess_CoQA.py
```

#### Step 4:
run the training code using:
```shell
python train_CoQA.py
```

#### Step 5:
Do prediction with answer thresholding using
```shell
python predict_CoQA.py -m models/best_model.pt --show SS
```
