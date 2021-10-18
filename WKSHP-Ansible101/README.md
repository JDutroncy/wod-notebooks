![HPEDEVlogo](Pictures/hpedevlogo-NB.JPG)         ![Ansible](Pictures/Ansiblelogo.png)

# Welcome to the Hack Shack
Powered by [HPE DEV Team](https://hpedev.io)

<p align="center">
  <img src="Pictures/hackshackdisco.png">
  
</p>

# Workshops-on-Demand

# Ansible101: A simple Introduction Ansible Concepts

Gone are the days when an administrator could, realistically, count the number of machines they were responsible for, and the days of very large scale deployments are here. This also means gone are the days when an admin could reasonably log into all of those machines to do the configuration by hand. Today it's best to rely on an automation framework to do this on a larger, more replicable, scale. Ansible is one such automation framework and this is a intended to walk folks through the very basics of Ansible, getting it set up, up and running, passing data, fetching information and generally getting comfortable with the basics of what configuration management is.

Ansible is an open-source software:
* configuration manager
* simple
* extensible via modules
* written in python
* broad community
* many external tools
* playbook repository
* used by openstack, openshift & tonns of project

It supports devices and things you wouldn’t expect:
* Servers, Switches and Routers (HPE, Aruba, Cisco, Arista, Dell)
* VMware
* Storage devices (HPE, Netapp, Pure Storage, etc)

In the following workshop, we will introduce the basics around Ansible. 

# Authors:[Frederic Passeron](mailto:frederic.passeron@hpe.com)    

## Handouts
You can freely copy the Jupyter Notebooks, including their output, in order to practice back at your office at your own pace, leveraging a local installation of Jupyter Notebook on your laptop.
- You install the Jupyter Notebook application from [here](https://jupyter.org/install). 
- A Beginners Guide is also available [here](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)


## Lab flow
HackShack Workshops are delivered through a central point that allows a portable, dynamic version of the lab guides. Rather than using standard PDF files which always end in copy / paste errors from the lab guide into the TS sessions, this year we decided to innovate and introduce a brand-new infrastructure. We will leverage a JupyterHub server on which all the different lab guides will be stored in a notebook format (*.ipynb).

In a nutshell, a notebook works as follows:

• A Notebook is a series of cells

• A Notebook uses a kernel (visible in the upper right corner of the Notebook)

• Cell can be Markdown or Code (in the selected kernel)

• To Run a cell use:

    o The Play Button at the top
    o Ctrl-Enter (run and stay on same cell)
    o Shift-Enter (run and move to next cell)
    
• Running a markdown cell is just rendering it

• Running a Code cell runs the code and display the output just below the cell

• When a cell is running it displays a [*] to its left, then when finished, it displays a counter of the number of execution of that cell

• You cannot run a cell when another is already running but you can interrupt a running cell with the stop button

Enjoy the labs ! :-)


## Workflow

### Lab 1: Authentication
Description: In this section, we’ll go through some of the necessary steps to retrieve the API Token necessary for authentication. Then we will look some of the components used to build, deploy a new instance.
* [Lab 1](1-WKSHP-VMAAS-Authentication.ipynb)

### Lab 2: Instance Creation
Description: In this section, we’ll go through some of basics actions to create an instance and then manage it (stop / start / suspend, etc...)
* [Lab 2](2-WKSHP-WKSHP-VMAAS-Instance.ipynb)

### Lab 3: Instance Management
Description: In this section, we’ll go through some additional instance management features like snapshotting, cloning.
* [Lab 3](3-WKSHP-VMAAS-Instance-Advanced.ipynb)


# Thank you!
![grommet.JPG](Pictures/grommet.JPG)


```python

```