# Dash sample with custom deployment script

The following code was taken from **Dash examples** here: https://dash.plotly.com/layout

> *Dash* is a Python framework for building analytical web applications. 
Built on top of Plotly.js, React and Flask, Dash ties modern UI elements like dropdowns, sliders, and graphs directly to your analytical Python code.

***
References to this framework:

* https://dash.plotly.com/
* https://github.com/plotly/dash

# Update Python version

- Review and change the Python version 
- Check in Kudu Python version list under **/opt/python/** and select the same version of your web app.
- Modify this parameter: **export PYTHON3="/opt/python/3.6.10/bin/python3.6"** in deploy.sh with the version you selected.
