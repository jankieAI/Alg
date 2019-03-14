Python
===

### Modules, Updates, Setup


[compile to another version](https://github.com/nvbn/py-backwards)
    ➜ py-backwards -i input.py -o output.py -t 2.7
    
[Nuitka, a Python compiler](http://nuitka.net/pages/overview.html)
 
[REPL, online compiler](https://repl.it/repls/FrugalOrderlyLearning)
 
[Junja2 - a template engine](http://jinja.pocoo.org/); [2.1](https://github.com/pallets/jinja/releases/tag/2.10)

[Snakemake workflow management system](http://snakemake.readthedocs.io/en/stable/) - is a tool to create reproducible and scalable data analyses

[Setting up Python for ML on Windows](https://realpython.com/python-windows-machine-learning-setup/)

[Machine Learning Tutorial](https://www.pyimagesearch.com/2019/01/14/machine-learning-in-python/)

[A Simple Guide to creating Predictive Models](https://medium.com/datadriveninvestor/a-simple-guide-to-creating-predictive-models-in-python-part-2b-7be3afb5c557)

https://medium.com/datadriveninvestor/a-simple-guide-to-creating-predictive-models-in-python-part-2b-7be3afb5c557)

[Features of Python3](https://github.com/arogozhnikov/python3_with_pleasure)

[Composing programs](https://composingprograms.com/)

[Algebraic Number Theory package](https://github.com/louisabraham/algnuth)

[The Python scientific stack, compiled to WebAssembly ](https://github.com/iodide-project/pyodide); see [demo](https://iodide.io/pyodide-demo/python.html)

[Pyodide, Python in a web browser](https://alpha.iodide.io/notebooks/222/)

[online translation server](https://github.com/translate/pootle)

### Conferences

[2017 Scipy Workshop](https://github.com/Andrewnetwork/WorkshopScipy)
[2019 PyCon](https://us.pycon.org/2019/)

#### Discussions

[Is PYthon the world's most popular language?](https://news.ycombinator.com/item?id=18182003)

### Algorithms

[Sort:](SORT/)

[Regex:](REGEX/)
Examples of regular expressions for matching patterns

[Graph:](GRAPH/)
A*, B*, Breadth-first, D*, Depth-first, Dijkstra's,..

Example of a graph with six nodes A-F and eight edges represented by Python dictionary:

graph = {'A': ['B', 'C'],

'B': ['C', 'D'],

'C': ['D'],

'D': ['C'],

'E': ['F'],

'F': ['C']}          

[Machine Learning:](ML/)

+ [ML Crash Course: The Bias-Variance Dilemma](https://ml.berkeley.edu/blog/2017/07/13/tutorial-4/)
+ [Reinforcement Learning](https://github.com/5vision)
+ [Chatfirst API](https://github.com/chatfirst/chatfirst)

+ [Open source deep learning models](https://github.com/samdeeplearning/The-Terrible-Deep-Learning-List)
+ [the future of deep learning](https://blog.keras.io/the-future-of-deep-learning.html)

+ [in-browser deep learning](https://tenso.rs/#readmore)

+ [Collaboratory](https://research.google.com/colaboratory/unregistered.html)

+ [Azure notebooks](https://notebooks.azure.com/)

+ [CoCalc](https://cocalc.com/) created by the SageMath developers


[Web:](WEB/)
Beautiful Soup is a Python library for pulling data out of HTML and XML files. 

easy_install beautifulsoup4

or better keep it in virtualenv:
sudo easy_install virtualenv
pip install BeautifulSoup4

+ [Data Science handbook]{(https://jakevdp.github.io/PythonDataScienceHandbook/)
+ [Statistics for Hackers](https://www.youtube.com/watch?v=Iq9DzN6mvYA)

[5 web scraping libraries](https://elitedatascience.com/python-web-scraping-libraries)
+The Farm: Requests
+The Stew: Beautiful Soup 4
+The Salad: lxml
+The Restaurant: Selenium
+The Chef: Scrapy


### Learning resources
* [Pytudes](https://github.com/norvig/pytudes) - Norvig's practice programs
* [Scipy Lecture Notes](http://www.scipy-lectures.org/) 
* [Python for Economics](http://quant-econ.net/py/index.html)
* [Quantitative Statistics](http://people.duke.edu/~ccc14/sta-663/)

* [Coconut](http://coconut-lang.org/), a functional programming language that compiles to Python



* [CS109 Data Science](http://cs109.github.io/2015/pages/videos.html)

* [Harvard Data Science](https://matterhorn.dce.harvard.edu/engage/ui/index.html#/2016/01/14328)

* [PYML - Machine Learning in Python](http://pyml.sourceforge.net/)

* [Neural network with Python and Theano](http://www.wildml.com/2015/10/recurrent-neural-network-tutorial-part-4-implementing-a-grulstm-rnn-with-python-and-theano/)

* [Theano Library](http://deeplearning.net/software/theano/)

* (https://www.cs.cmu.edu/~ymiao/pdnntk.html) - PDNN: A Python Toolkit for Deep Learning

* [Intro to Python for CS & Eng](http://www.southampton.ac.uk/~fangohr/training/python/pdfs/Python-for-Computational-Science-and-Engineering.pdf)

* [Platform for learning bioinformatics](http://rosalind.info/problems/locations/)

* [Matrix Calculus](http://www.matrixcalculus.org/)

* [API checklist](http://python.apichecklist.com/)

* [Numerical Python, fast and sophisticated arrays](http://sourceforge.net/projects/numpy/) - [python 2.7](https://github.com/numpy/numpy/blob/master/doc/neps/dropping-python2.7-proposal.rst)

* [Python cheet sheets](https://www.pythonsheets.com/)

* [Pythonic Data Structures and Algorithms](https://github.com/keon/algorithms)

    git clone git://github.com/numpy/numpy.git numpy

    http://matplotlib.org/ - python 2D plotting library

If you get an ImportError: No module named matplotlib

set your PYTHONPATH, eg: export PYTHONPATH=/Library/Python/2.7/site-packages:$PYTHONPATH

    git clone git://github.com/scipy/scipy.git scipy

PyAudio provides Python bindings for PortAudio, the cross-platform audio I/O library 

to play and record audio on a variety of platforms.

http://people.csail.mit.edu/hubert/pyaudio/

[Simple way to access google api for speech recognition with python](https://pypi.python.org/pypi/pygsr)
pip install pygsr

[A grammar of graphics for python](https://github.com/has2k1/plotnine)

[wrapper providing R's ggplot2 syntax](https://github.com/sirrice/pygg)

### UI

+ PyQT5, [Python GUI](https://build-system.fman.io/pyqt5-tutorial)

### Testing

pip install selenium  # Downloading Python bindings for Selenium
(for windows: C:\Python35\Scripts\pip.exe install selenium)

Place drivers in /usr/bin or /usr/local/bin

|Browser	| Popular Drivers                                                       	|---	|
|---------	|-----------------------------------------------------------------------	|---	|
| Chrome  	| https://sites.google.com/a/chromium.org/chromedriver/downloads        	|   	| 
| Edge    	| https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/ 	|   	|
| Firefox 	| https://github.com/mozilla/geckodriver/releases                       	|   	|  
| Safari  	| https://webkit.org/blog/6900/webdriver-support-in-safari-10/          	|   	| 

Cons: Selenium tests are unstable, time to maintain and run, low ROI

Old school: Ranorex, LeanFT, TestComplete, Telerik and Sahi; Fantom.js, Mocha, Jasmine and Protractor; Screenster

[Testing with Cucumber and Capybara](https://www.gamesparks.com/blog/automated-testing-with-cucumber-and-capybara/)

### Datasets

[Google dataset search](https://toolbox.google.com/datasetsearch)

[open source](https://deepmind.com/research/open-source/open-source-datasets/)

[A RESTish web API for climate change related data](http://api.carbondoomsday.com); [github](https://github.com/giving-a-fuck-about-climate-change/carbondoomsday)

[Global average temperatures](https://www.nsstc.uah.edu/climate/)[direct link](http://www.nsstc.uah.edu/data/msu/v6.0beta/tlt/uahncdc_lt_6.0beta5.txt)

[cold and warm episodes by season](http://www.cpc.noaa.gov/products/analysis_monitoring/ensostuff/ensoyears.shtml)

[sea level information](http://sealevel.colorado.edu/)


### Security
[Gnupg](https://bitbucket.org/vinay.sajip/python-gnupg/) - Python library which takes care of the internal details and allows its users to generate and manage keys, encrypt and decrypt data, and sign and verify messages. See also
[github mirror](https://github.com/isislovecruft/python-gnupg)

### administration
updating 2.7.x on mac  (https://www.python.org/downloads/)

sudo rm -R /System/Library/Frameworks/Python.framework/Versions/2.7

sudo mv /Library/Frameworks/Python.framework/Versions/2.7 /System/Library/Frameworks/Python.framework/Versions

sudo chown -R root:wheel /System/Library/Frameworks/Python.framework/Versions/2.7

sudo rm /System/Library/Frameworks/Python.framework/Versions/Current

sudo ln -s /System/Library/Frameworks/Python.framework/Versions/2.7 /System/Library/Frameworks/Python.framework/Versions/Current

sudo rm /usr/bin/pydoc

sudo rm /usr/bin/python

sudo rm /usr/bin/pythonw

sudo rm /usr/bin/python-config

sudo ln -s /System/Library/Frameworks/Python.framework/Versions/2.7/bin/pydoc /usr/bin/pydoc

sudo ln -s /System/Library/Frameworks/Python.framework/Versions/2.7/bin/python /usr/bin/python

sudo ln -s /System/Library/Frameworks/Python.framework/Versions/2.7/bin/pythonw /usr/bin/pythonw

sudo ln -s /System/Library/Frameworks/Python.framework/Versions/2.7/bin/python-config /usr/bin/python-config

---

sudo easy_install pip  // pip install --upgrade pip

sudo easy_install -U numpy

pip install scipy

pip install matplotlib
