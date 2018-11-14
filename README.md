# NSF 2D Framework Workshop November 2018

##### Shared files for 2018 NSF 2D Materials Data Framework Training Workshop training organized by PARADIM and NIST
---

## Handy Resources:

1. Rendering JSON in a notebook: [https://github.com/caldwell/renderjson](https://github.com/caldwell/renderjson)
2. JSON is the most common data serialization format you run into in data science. It's a simple way to pass data between servers, clients, programs, websites... all kinds of things. It's the format of Jupyter notebooks and a way structured data can be represented as a Javascript Object. You don't really need to know a lot about it most of the time, but if you want to better understand it try:
  * [https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) 
  * [https://www.json.org](https://www.json.org)
3. YAML (rhymes with "camel") is another data serialization format. In classic computer science tradition the name is meant to be humorous; it stands for "YAML ain't markup language"). It's meant to be more human readable than JSON and is just a superset of JSON that gives importance to indentation and newlines in the style of Python. You see YAML used a lot to store configurations of programs.  For more info you can check out:
  * [https://learnxinyminutes.com/docs/yaml/](https://learnxinyminutes.com/docs/yaml/)
4. Conda is a package, dependency, and environment manager. It's available free for many interesting languages and we use it for Python. Your containers already have it installed which means you can use it from the terminal shell (or even within a notebook by using magics). Open a new terminal and try: conda info --envs.  It will tell you what environments are preinstalled.  You can see what packages are already installed by using conda list. There's a cheat sheet for Conda in our workshop GitHub repository.  Learn more at: [https://conda.io/docs/](https://conda.io/docs/).
5. Plotting is one of the most common and useful things in science or engineering. Python offers an incredible range of options, but almost everyone starts with the matplotlib library. Matplotlib is particularly great because it now works pretty seamlessly with Pandas. The online documentation ([https://matplotlib.org](https://matplotlib.org)) is really helpful when you are getting started or when you need something new. There is also a nice Python Plot Gallery you can check out here: [https://python-graph-gallery.com/matplotlib/](https://python-graph-gallery.com/matplotlib/). Seaborn builds on matplotlib and is a nice next step. Check out the nice Seaborn tutorial here: [https://jakevdp.github.io/PythonDataScienceHandbook/04.14-visualization-with-seaborn.html](https://jakevdp.github.io/PythonDataScienceHandbook/04.14-visualization-with-seaborn.html). Finally, Bokeh adds a lot of nice esthetics as well as interactive tools. If you want to create plots with sliders or that people can grab and rescale, Bokeh offers a lot of options. The best starting place for Bokeh is probably the source: [https://bokeh.pydata.org/en/latest/](https://bokeh.pydata.org/en/latest/). I really like the Bokeh tutorial found here on GitHub: [https://github.com/bokeh/bokeh-notebooks](https://github.com/bokeh/bokeh-notebooks); git clone it into your personal storage space (Temporary or Persistent) and check in out.


## Interesting Reading:

1.  JupyterCon is expensive, but a really fun way to see a lot of the Jupyter Landscape in one place. Here's an intriguing review: [http://willcrichton.net/notes/lessons-from-jupytercon/](http://willcrichton.net/notes/lessons-from-jupytercon/)
