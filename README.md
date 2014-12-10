TouchCandy
==========

Sending pixels from TouchDesigner to Fadecandy

Based on Micah Scott's Fadecandy project: https://github.com/scanlime/fadecandy

Fadecandy forum: https://groups.google.com/forum/#!forum/fadecandy


The modified opc.py included in this repo, goes to: \Derivative\TouchDesigner088\bin\Lib

The included conf.json is modified for 60 pixel strips.

The TouchDesigner patch is a simple network, converting video TOP to text based DAT.
The 'executeDAT' in Touch, sends the pixels to the server, which you need to have in the receiving end.

**
