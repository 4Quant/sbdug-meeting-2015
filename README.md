# Making Scaling Simple: Using Big Data to Improve Imaging 

The presentation __[as slides](https://rawgit.com/4Quant/sbdug-meeting-2015/master/microscopy-big-data.html)__, __[as a handout](https://rawgit.com/4Quant/sbdug-meeting-2015/master/printable.html)__, __[as printable pdf](https://rawgit.com/4Quant/sbdug-meeting-2015/master/printable.pdf)__

## Kevin Mader (4Quant and ETH Zurich)
The presentation given at Swiss Big Data Users Group (http://www.bigdata-usergroup.ch/item/816648) on image processing on large, diverse datasets using [Apache Spark](http://spark.apache.org) as a back-end.

Kevin Mader is the founder of 4Quant(http://www.4quant.com) and lecturer in the X-ray Microscopy Group within the Department for Information Technology and Electrical Engineering at ETH Zurich. His research focuses on turning big hairy 3D images into simple, robust, reproducible numbers without resorting to black boxes or magic. In particular, as part of several collaborations, he is currently working on automatically segmenting full animal zebrafish images, characterizing rheology in 3D flows, and measuring viral infection dynamics in cell lines.

## Summary
Recent improvements in acquisition, detectors, and automation in imaging science has meant that medical doctors and biologists now regularly encounter terabyte-sized datasets which well-exceed the scope for individual, manual analysis. To confront this issue we have adopted tools and approaches from the Big Data community to make scaling up to and beyond terabytes easy.

## Learn more at 
- 4Quant: From Images to Statistics - http://www.4quant.com
 - DeepZoom images: http://people.ee.ethz.ch/~maderk/dz/tomcat.html
- Spark Demo from this presentation - https://gist.github.com/kmader/755c2d99c23f4cbe2e74
- Setting up Spark on a Cluster
 - using Sun Grid Engine - https://github.com/4Quant/sge_spark
 - using MPI Jobs - https://bitbucket.org/skicavs/spark-on-brutus)
- Setting up Spark on the Cloud https://4quant.github.io/aws-spark-introduction

### Imaging
- X-Ray Imaging Group at ETH Zurich - http://bit.ly/1gD8wKb
- Quantitative Big Imaging Course at ETH Zurich - http://bit.ly/1kj9mnq
- Presentation at Spark Summit 2014 - https://rawgit.com/4Quant/spark-summit-2014-presentation/master/ssPresentation.html
- Simple Hyperspectral Example - https://gist.github.com/kmader/e6fb564f4c180b87042f
- Flat-field correction and sinogram creation demo - https://gist.github.com/kmader/7cce1e04f74fdc990dfe

### Beyond Image Processing
- FEM Demo using GraphX - https://gist.github.com/kmader/6456262935af381c8dbe
