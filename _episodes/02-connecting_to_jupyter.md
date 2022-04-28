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

In this tutorial we will show you how to run the Jupyter notebooks using [Google Co-lab](https://colab.research.google.com/). 

**Step 1:** You will login with your google account.  

**Step 2:** Once you login successfully, you should be presented with a dialog and you can select the Github tab and paste in the following URL **https://github.com/tapis-project/Smart-Data_Collection_for_sensor_networks_notebook** and then hit the search icon.  

**Step 3:** You will then be shown a list of files you can select Smart-Data_Collection_for_sensor_networks.ipynb file and the the far button on the left (Open notebook in new tab).

**Step 4:** Now you need to install the 3 python library dependences in the colab. Add a code cell at the top of the notebook and paste the following in that cell and run it.

```!pip install tapipy pandas matplotlib```

**Step 5:** After running the above code you need to restart the runtime - go to the **Menu** and select **Runtime -> Restart runtime** or use **CTRL+M** on the keyboard.  Now you can execute the code in the notebook and follow the rest of the tutorial.


## Alternate Method: Creating a Jupyter notebook server with MyBinder

You can access a Jupyter notebook with python scripts demonstrating the usage of the Tapis Streams API with MyBinder too. 

### Deploying a Jupyter notebook server using MyBinder

Go to the [MyBinder](https://mybinder.org/v2/gh/tapis-project/Smart-Data_Collection_for_sensor_networks_notebook/HEAD) notebook link in a web browser.

This should launch a jupyter environment with all the dependencies and notebook for this workshop.
