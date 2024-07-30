# Insurance Premium Prediction


### Problem Statement:<br>
The goal of this project is to give people an estimate of how much they need based on their individual health situation. After that, customers can work with any health insurance carrier and its plans and perks while keeping the projected cost from our study in mind. This can assist a person in concentrating on the health side of an insurance policy rather han the ineffective part.

### Approach: <br>
The classical machine learning tasks like Data Exploration, Data Cleaning,Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms that’s best fit for the above case.
Some Famous Algorithms: - Linear Regression, Random Forest and Gradient Boosting, Decision tree etc.

### Results: <br>
We have to build a solution that should able to predict the premium of the personal for health insurance.

<br>
FOR DOCUMENTATION OF THIS PROJECT VISIT HERE:[DOCS](https://github.com/ShridattaP20/Insurance_Premium_Prediction/tree/main/Docs)
<br>

### STEPS ARE MENTIONED BELOW FOR MAKING THE ENTIRE PIPELINE
step1 :
``` bash
conda create -p envname python=3.8
```
step2 :
Create ```setup.py``` in root dir it is help us to create python package.

After steps open up vscode or pycharm terminal<br>
Follow these commands<br>
1.```pip install -r requirements.txt```<br>
2.```git init```<br>
3.```git add .```<br>
4.```git commit -m "committed"```<br>
5.```git remote add origin git repo https address```<br>
6.```git branch -M main```<br>
7.```git push origin main```<br>

step 3:<br>
Inside the ```src``` dir create ```logger.py``` file ```utils.py``` file ```exception.py```file<br>

The main objective for this file is to write a ```function``` which will handle the custom exception, logging details.<br>

step 4:<br>
Inside the ```src```  ```components``` dir create ```data_ingestion.py``` file ```data_transformation.py``` file ```model_trainer.py```file<br>

The main objective for this file is to write a ```function``` which will fetch ```.csv``` file and do data transformation and model training.<br>

step 5:<br>
After evaluating the model, save and dump it to **artifacts** directory.

step 6:<br>
Inside the ```src```  ```pipiline``` dir create ```predict_pipeline.py``` file.<br>

The main objective for this file is to write a ```function``` which will use to automate the entire prediction process.<br>


step 7:
All our procedure fininshed
Now time to create webapp
```bash
├───static
│   └───css
│           main.css
│
└───templates
        home.html
        index.html
```
step 8:
```app.py``` on root dir for creating flask api
Now make routes like `\` for rendering home page and `/predictdata` for rendering predictions.

### Thank You
