https://www.youtube.com/watch?time_continue=2484&v=N0lxfilGfak


41:50

=====================================================

how to extract  csv data from webpage  

=======================================================================
kaggle.com/Bejoysevadas

https://www.kaggle.com/Bejoysevadas

======================================================================


https://www.youtube.com/watch?v=MjwWzBiAMck

**************************************
from urllib import request

goog_url = 'http://samplecsvs.s3.amazonaws.com/Sacramentorealestatetransactions.csv'
def download(csv_url):
    response = request.urlopen(csv_url)
    csv = response.read()
    csv_str = str(csv)
    lines = csv_str.split("\\n")
    dext_url = 'goog.csv'
    fx = open(dext_url, "w")
    for line in lines:
        fx.write(line + "\n")
    fx.close()

download(goog_url)

https://www.youtube.com/watch?v=vmEHCJofslg ---> pending to watch   (jupyter1)


=====================================================
mat lab --> read

https://www.oreilly.com/library/view/python-data-science/9781491912126/ch04.html

=====================================================
