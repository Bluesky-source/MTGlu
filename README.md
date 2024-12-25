# MTGlu

## 🛠️ Install

**Implementation Environment**: Using this command to implement your environment.

```
conda create -n MTGlu python=3.10
conda activate MTGlu
pip install -r requirements.txt
```

## 🍬 Datasets

This work based on the OhioT1DM dataset and a ChileT1DM dataset.

OhioT1DM data: http://smarthealth.cs.ohio.edu/OhioT1DM-dataset.html.

ChileT1DM data: https://github.com/salangarica/Probabilistic_Glucose_Prediction


## 🕹️ Quickstart

### 1.Processing

We need to process the OhioT1DM data into the following format.

| index | glucose | 
| :----:| :---: | 
| 2027-06-29 13:40:00 | 142.0 | 
| 2027-06-29 13:45:00 | 136.0 | 

### 2.Train

We use the architecture provided by Darts to train our model as well as the baseline model.

Code will be available once the paper is published.

## ❤️ References

The code refers to the repo [Darts](https://github.com/unit8co/darts)
