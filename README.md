# VideoSummarizeAlgorithm
Video Summarizer Test Algorithm

Current approach involves use of clustering ML algorithms from SKLearn. 
For this implementation, KMeans clustering with 50 clusters works best for test video about 45 minutes long. PCA analysis also indicates OPTICS algorithm holds promise. 

Video can be outputted and edited with given time positions through moviepy library.

Clustering methods provide lots of variability between supposed important aspects of video. Next step would be to attempt with more supervised learning. 
