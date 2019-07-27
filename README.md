# common_convolutions
Examining 3x3 convolutional filters that are common in pretrained object recognition networks.
Networks used (from Pytorch): resnet18, alexnet, squeezenet, vgg16, inception

Information about the top 100 filters in filters.txt

Note: only input convs included as of now

--------------
#### Example - plus sign
![common convs](https://github.com/arnokha/common_convolutions/blob/master/popular_convs.png)

#### Example - point
![common convs](https://github.com/arnokha/common_convolutions/blob/master/dot_convs.png)

#### Example - horizontal line
![common convs](https://github.com/arnokha/common_convolutions/blob/master/line_convs.png)

-------------
#### TODO (maybe)
 1. Include description of filters (interpretation of what they do).
 2. Aggregate multiples of the same filters together.
 3. Frequency by what layers they occur in (bottom 1/3, middle 1/3, top 1/3)
 4. Include output filters
