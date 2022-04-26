---
title: "Connecting to Jupyter"
teaching: 5
exercises: 5
questions:
- "Running Jupyter notebooks using Google Co-lab?"
objectives:
- "Use Google Co-lab to access a Jupyter notebook for Smart-Data collection for sensor networks."
---
# Running a Jupyter notbook using Google Co-lab

In this tutorial we will show you how to run the Jupyter notebools using [Google Co-lab] (https://colab.research.google.com/) and login with you google account.  You should be presented with a dialog and you can select the Github tab and paste in the following [URL](https://github.com/tapis-project/Smart-Data_Collection_for_sensor_networks_notebook) and then hit the search icon.  You will then be shown a list of files you can select Smart-Data_Collection_for_sensor_networks.ipynb file and the the far button on the left (Open notebook in new tab).

Now you need to install the 3 python library dependences in the colab. Add a code cell at the top of the notebook and paste the following in that cell and run it.

```!pip install tapipy pandas matplotlib```

After running the above code you need to restart the runtime - go to the menu and select Runtime -> Restart runtime or use CTRL+M on the keyboard.  Now you can execute the code in the notebook and follow the rest of the tutorial.


## Alternate Method: Creating a Jupyter notebook server with MyBinder

You can access a Jupyter notebook with python scripts demonstrating the usage of the Tapis Streams API with MyBinder too. 

### Deploying a Jupyter notebook server using MyBinder

Go to the [MyBinder](https://mybinder.org/v2/gh/scleveland/Smart-Data_Collection_for_sensor_networks_notebook/HEAD?labpath=Smart-Data_Collection_for_sensor_networks.ipynb) notebook link in a web browser.

This should launch a jupyter environment with all the dependencies and notebook for this workshop.


## Alternate Method: Using Docker

If you wish to run this locally and you have Docker installed you can use the following command:

```docker run -p 8888:8888 scleveland/streams-tutorial:latest```

You will see the standard output from the above command result in a URL that looks like http://127.0.0.1:8888/?token=369db183f7c0e018dca647914f5c56760ab80a25087a3656 that you can copy into your browser and access the jupyter lab session and the notebook. Once loaded in the browser you can continue with the tutorial.
