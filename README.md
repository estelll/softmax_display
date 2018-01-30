A simple display of softmax. Just open *softmax.html*.

## Usage
You can type in an array of float numbers on the landing page. 
**Please split your number with comma and make sure you've put in valid number, otherwise it will show nothing.**

In the header, there are four buttons:
* Stack a softmax layer: stack a softmax layer on the current result, that is, input the current softmax result into the next layer like: softmax(softmax(original input))
* Remove a softmax layer: opposit to the function above
* Add data with value: add a number into the array, and the softmax results will be automatically produced and added into the chart
* Delete data by id: delete an element in array by id which is the number in labels of x-axis

At the bottom, there are several sliders which are corresponding to the number in array. You can slide it to change the value of the number in array. Or you can type in the wanted number in the textbox beneath it. Numbers range from 0 to 100 are supported. Steps in slider is 0.1