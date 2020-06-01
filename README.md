# DataStreamProcessing
Processing Data Streams on Mobile Devices
Mitra Kazemzadeh
Wendy Osborn
University of Lethbridge
Mitra.kazemzadeh@uleth.ca

introduction:
with the increased usage of mobile devices, processing queries from data streams is a real possibility which will permit processing to happen anywhere. In traditional database management systems, the data needed to be stored in storage first in order to be processed. There are some applications that generate data streams instead of data sets. For instance, applications for monitoring the network traffic. These kinds of stream-oriented applications need a better way of storage management system than the traditional database management systems. With unbounded data received rapidly and constantly, the data needs to be processed instantly. Considering that we are dealing with bounded storage this seems impossible with the traditional database management systems. 
This issue would be more applicable to data streaming on mobile devices considering the limited storage space we are dealing with.
In this paper we focused on analyzing an application developed in Android Studio to process a query. The query involves Select, Projection and Join. We would perform it on two data streams received constantly. We introduce our architecture for processing the query over these data streams which handles the job by least amount of storage possible. For the select and projection we would produce the result with no need to access the storage. For the Join part of the query we would need a reasonable amount of storage to calculate the final result.
In section two we have discussed the previous work that has been done regarding stream processing and continuous queries over data streams.

