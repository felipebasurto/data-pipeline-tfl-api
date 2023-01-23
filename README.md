# data-pipeline-tfl-api
The London transportation organization "Transport for London" has a completely open and free web API that can extract thousands of real-time data about the city, you can find it here: "https://api.tfl.gov.uk/". 
Once we defined what we were going to extract from this API (in this case the city bus routes), we connected it to our Apache Nifi flow, which is responsible for extracting all this information and processing it so that it is later stored in Hadoop in an ordered and correct way according to the date and time at which these data were collected. 
Once the data is stored in Hadoop, we can extract it from the Spark notebook to read and process it.
