# X-ray Data Analysis - Aditya Workshop (Manipal)

## Setting up necessary software

## Option 1: Linux OS with Jupyter notebook

### Installing Sherpa

* Install Anaconda.
* `$ conda install -c sherpa sherpa`

### Installing Sunxspex

* `$ git clone https://github.com/abhilash-sw/sunxspex.git`
* `cd sunxspex`
* `$ git checkout manipal_workshop`
* `cd sunxspex`
* Open thermal.py and change `abs_path` (line no. 17) variable to current directory path (eg /home/mcns/manipal_workshop_x_ray/sunxspex/sunxspex)
* Open io.py and change `abs_path` variable to current directory path
* `cd ..`
* `python setup.py install`

## Option 2: [Colab](https://colab.research.google.com/)
