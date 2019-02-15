This archive contains a data set of 1 000 000 timestamped GPS points collected from Twitter. Those points correspond to tweets where the content has been removed for privacy issues. 

There is a single entry per line, and the format of each line is:
unix_timestamp tab longitude space latitude

you can interpret the pair (longitude,latitude) as a point in the 2D euclidean space and use the the euclidean distance to compute the distance between the points. 
