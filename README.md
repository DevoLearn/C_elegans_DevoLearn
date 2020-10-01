# *C. elegans* DevoLearn
Web App to support the _C. elegans_ part of the Devolearn library. 

## What is it?
This is a web app implementation of _C.elegans_ part of the Devolearn library. For the researchers out there who are not very familiar with programing but are in need to use Machine lerning and Neural networks to accelerate their research can use this tool. 

It is a highly interactive and user friendly tool to get quick results, with all the information of _C.elegans_ Embrogenesis process. 

## Repository Tree

Below is the repository tree to indicate where which files are being located.

<pre>

│   app.py
│   Aptfile
│   Procfile
│   requirements.txt
│   runtime.txt
│
├───static
│   │   devoworm-logo.png
│   │   google_summer_of_code.png
│   │   incf.png
│   │   openworm.jpeg
│   │
│   ├───css
│   │   │   css-main.css
│   │   │   css-noscript.css
│   │   │
│   │   └───styles
│   │           bootstrap_min.css
│   │           font_awesome_min.css
│   │           min.css
│   │
│   ├───images
│   │       22.gif
│   │       3d_segmentation_preds.gif
│   │       DevoLearn.gif
│   │       generated_embryos_3.gif
│   │       images-bg.jpg
│   │       images-overlay.png
│   │       images-pic01.jpg
│   │       images-pic02.jpg
│   │       images-pic03.jpg
│   │       resnet_preds_with_input.gif
│   │       worm_stages.jpg
│   │
│   ├───js
│   │       js-jquery.min.js
│   │       js-main.js
│   │       js-skel.min.js
│   │       js-util.js
│   │
│   └───styles
│           bootstrap_min.css
│           font_awesome_min.css
│           min.css
│
├───templates
│       index.html
│       result.html
│
└───__pycache__
        app.cpython-38.pyc

</pre>
## How to use it?

This tool is part of [DevoWormAI](https://devoworm.github.io/DevoWormAi/index.html). More over, this tool also provides reseachers all necessary code by the means of Google Colab notebooks which can be found in this directory. This notebook is for those who have understanding of Machine learning and neural networks and they can tweak the params according to their need for the best results.

## Online Resource

If you want to try out our online tool, please visit - [OpenDevoCell](https://celegans-devolearn.herokuapp.com/)
For more of our research and tools, please visit our Home Page - [DevoWormAI](https://devoworm.github.io/DevoWormAi/index.html)

## Can I use it on my local machine?

Yes, it is a web app that you can easily install and run on your device. Please Follow the below instructions to proceed.

Step 1- Clone this repo in your Computer.
Step 2- Unzip the contents into desired folder.
Step 3- Go to your Terminal/Command Prompt(CMD) and navigate to the folder where you have extracted files.
Step 4- Create a Virtual Environment by using the below command.
* For macOS and Linux use
```python
python3 -m pip install --user <your_virtual_env_name>
```
* For Windows use
```python
py -m pip install --user <your_virtual_env_name>
```

Step 5- After creating virtual environment, enter in it using command.
```python
source <your_virtual_env_name>/bin/activate
```

Step 6- Now, install all the required packages using requirements.txt using command.
```python
pip install -r requirements.txt
```
Step 7- Now, all the installation process is done, and is done correctly, app is ready to run. To run the app, use command.
```python
python3 -m flask run
```

# Version
Version Info: V-0.0.1

## Contact us
### Authors/maintainers:
* [Ujjwal Singh](https://twitter.com/ujjjwalll)
* [Mayukh Deb](https://twitter.com/mayukh091)
* [Dr. Bradly Alicea](https://twitter.com/balicea1)

Feel free to join our [slack](https://openworm.slack.com/archives/CMVFU7Q4W)!
