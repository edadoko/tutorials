1. Install Dependencies
	1. Check if you have pip: `pip --version` 
	If not:
		1. Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py)
		2. Open a command prompt and navigate to the folder containing `get-pip.py`.
		3. Run the following command: `python get-pip.py`

	2. Check if you have pyenv: `virtualenv --version` 
	If not:
	   1. Run `pip install virtualenv`

2. Set up Environment
     1. Navigate to your working directory and the virtual env, this one is called 'juptyer_env': `virtualenv jupyter_env`
     2. Activate the environment: `source jupyter_env/bin/activate`
     3. ... Work in your environment ... (*)
     4. Deactivate the environment `deactivate jupyter_env`
     
(*) 3. Install jupyter: `pip install jupyter`

4. Run jupyter: `jupyter notebook`
If this works you should have a ![Browser Screen](/images/localhost_img_1.png) popup. 

# Jupyter Notebooks
A Jupyter notebook lets you write and execute Python code in your web browser. It makes it very easy to tinker with code and execute it in bits and pieces; for this reason IPython notebooks are widely used in scientific computing.
You can see all notebooks abvailable with the .ipynb extension. Continue exploring on the Jupyter Tutorial notebook. 

Resources: 
* Markdown: https://guides.github.com/features/mastering-markdown/
* Virtualenv: https://virtualenv.pypa.io/en/latest/