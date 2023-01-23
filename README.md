# data-pipeline-tfl-api
The London transportation organization "Transport for London" has a completely open and free web API that can extract thousands of real-time data about the city, you can find it here: "https://api.tfl.gov.uk/". 
Once we defined what we were going to extract from this API (in this case the city bus routes), we connected it to our Apache Nifi flow, which is responsible for extracting all this information and processing it so that it is later stored in Hadoop in an ordered and correct way according to the date and time at which these data were collected. 
Once the data is stored in Hadoop, we can extract it from the Spark notebook to read and process it.
![Sin título-1](https://user-images.githubusercontent.com/62935664/214018873-484c778d-8a74-4e24-aa63-26e34623f17b.jpg)
