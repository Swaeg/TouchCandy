TouchCandy
==========

Sending pixels from TouchDesigner to Fadecandy

UPDATE: This patch does not work with newer versions of Touchdesigner. 
To remedy this, you have to convert the table to output values between 1-255 instead of 0-255. Will update the patch asap


---


Based on Micah Scott's Fadecandy project: https://github.com/scanlime/fadecandy

Fadecandy forum: https://groups.google.com/forum/#!forum/fadecandy

You can download Touch from: https://www.derivative.ca/088/Downloads/


The modified opc.py included in this repo, goes to: \Derivative\TouchDesigner088\bin\Lib

The included conf.json is modified for 60 pixel strips.

The TouchDesigner patch is a simple network, converting video TOP to text based DAT.
The 'executeDAT' in Touch, sends the pixels to the server, which you need to have in the receiving end.

**
