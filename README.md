
### Steps to create a venv and assign as kernel for jupyter notebook
$ python -m venv projectname
$ source projectname/bin/activate
(venv) $ pip install ipykernel
(venv) $ ipython kernel install --user --name=projectname

Open and close vcode

Reference:
https://anbasile.github.io/posts/2017-06-25-jupyter-venv/