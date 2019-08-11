# olympics

This is a simple example how to use Bokeh server.

To build this project, we used data from https://www.theguardian.com/sport/datablog/2012/jun/25/olympic-medal-winner-list-data#data.
We rearranged the data a little bit so that we could see how many medals type each country had won per year. After that, we added a second graphic that tells us how many medals men and women had won by country and by year.

To run it, just download the Jupyter notebook and save it locally. You can acess it using Anaconda Navigator and then opening JupterLab, or you can use Google Colaboratory.
After getting acess to the code, just use the code editor you like the most and save it with '.py' extension.
Finally, open your promp and run the following command:

bokeh serve --show myapp.py
