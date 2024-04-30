# bbb

In [this business article](https://edition.cnn.com/2023/04/26/business/bed-bath-beyond-merchandise-dg/index.html) from 2023 by CNN, I came across a chart where data is represented in a hierarchical manner.

I searched a lot for the exact table of data (numbers) that were visualized by the chart, but failed. Then I came up with an idea of extracting data from the chart itself. Still I could not come up with accurate numbers: all I have is the size of each circle, relative to others. 

Using MS Paint, I edited the original image into two different images:
- [an image with only bounding circles](https://github.com/ArnobTurja2002Ghosh/bbb/blob/main/Untitled1.png)
- [an image without the bounding circles](https://github.com/ArnobTurja2002Ghosh/bbb/blob/main/Untitled.png)

Using cv2 library of python, I found the size (in pixels) of every circle; using pandas I created a dataframe of the numbers; and using Circlify and Matplotlib, I created my own version of "How big was the 'beyond' section at Bed Bath & Beyond?" All I would need now is the number of links in one of the subcategories and I can find the links in each of the subcategories.
