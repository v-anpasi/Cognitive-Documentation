<!--
NavPath: Emotion API/Tutorials
LinkLabel: Get Started in Python Tutorial
Url: Emotion-api/documentation/tutorials/GetStartedWithPython
Weight: 45
-->

#Emotion API using Python Tutorial

To make it easy to get started with the Emotion API, the Jupyter notebook linked below shows you how to use the API in Python and how to visualize your results using some popular libraries. 

[Emotion API Python Tutorial Notebook](https://github.com/Microsoft/Cognitive-Emotion-Python/blob/master/Jupyter%20Notebook/Emotion%20Analysis%20Example.ipynb)

###Using the Jupyter Notebook

To use the notebook interactively, you will need to clone it and run it in Jupyter. To learn how to get started with interactive Jupyter notebooks, refer to: [Jupyter Documementation](http://jupyter.readthedocs.io/en/latest/index.html). 

To run the tutorial, you will need a subscription key for the Emotion API. Visit the [Subscription page](https://www.microsoft.com/cognitive-services/en-us/sign-up) to sign up. On the “Sign in” page, use your Microsoft account to sign in and you will be able to subscribe and get free keys. After completing the sign-up process, paste your key into the variables section of the notebook (reproduced below). Either the primary or the secondary key works.

```
#Variables

_url = 'https://westus.api.cognitive.microsoft.com/emotion/v1.0/recognize'
_key = None #Here you have to paste your primary key
_maxNumRetries = 10
```
