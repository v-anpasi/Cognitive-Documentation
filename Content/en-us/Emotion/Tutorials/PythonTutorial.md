<!--
NavPath: Emotion API/Tutorials
LinkLabel: Get Started in Python Tutorial
Url: Emotion-api/documentation/tutorials/GetStartedWithPython
Weight: 45
-->

#Emotion API using Python Tutorial

This tutorial shows you how to use the Emotion API in Python and how to visualize your results using some popular libraries. Use Jupyter to run the tutorial. To learn how to get started with interactive Jupyter notebooks, refer to: [Jupyter Documementation](http://jupyter.readthedocs.io/en/latest/index.html). 

###Opening the Tutorial Notebook in Jupyter

1. Navigate to the [tutorial notebook in GitHub](https://github.com/Microsoft/Cognitive-Emotion-Python).
2. Click on the green button to clone or download the tutorial.
3. Open a command prompt and go to the folder _Cognitive-Emotion-Python-master\Cognitive-Emotion-Python-master\Jupyter_ Notebook.
4. Run the command **jupyter notebook** from the command prompt. This will start Jupyter.
5. In the Jupyter window, click on _Emotion Analysis Example.ipynb_ to open the tutorial notebook

###Running the Tutorial

To run the tutorial, you will need a subscription key for the Emotion API. Visit the [Subscription page](https://www.microsoft.com/cognitive-services/en-us/sign-up) to sign up. On the “Sign in” page, use your Microsoft account to sign in and you will be able to subscribe and get free keys. After completing the sign-up process, paste your key into the variables section of the notebook (reproduced below). Either the primary or the secondary key works. Make sure to enclose the key in quotes to make it a string.

```
#Variables

_url = 'https://westus.api.cognitive.microsoft.com/emotion/v1.0/recognize'
_key = None #Here you have to paste your primary key
_maxNumRetries = 10
```
