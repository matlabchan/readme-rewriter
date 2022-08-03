# readme-rewriter
## Test for image resizing g2531455
This repository is used to test g2531455 for readme rewriting for File Exchange submissions.

Adding this line to see if I can update from Git on MATLAB Desktop

| Left Justified    | Centered       | Right Justified     |
|:--                |:--------------:|                  --:|
| Gauche            | Centre         | Droit               |

| Image Test        | Image Test     |  Image 40px tall    |
|:-----------------:|:--------------:|:-------------------:|
| 1234567           | 123456         | <a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" max-height="40px" /></a>|

| Image Test        | Image Test     |  Image -40px tall    |
|:-----------------:|:--------------:|:-------------------:|
| 1234567           | 123456         | <a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" max-height="-40px" /></a>|

| Image Test        | Image Test     | Image invalid height|
|:-----------------:|:--------------:|:-------------------:|
| 1234567           | 123456         | <a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" height="dummy-value" /></a>|

## Test for updated mailto links g2550628
[Test for Chandler](mailto:ccrane@mathworks.com)
[Test for Fake](mailto:fake@mathworks.com)

## Test for newlines in summary (update the summary with newlines) g2469144

# New Test for Height
### With height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" height="745px" /></a>

### With max-height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" max-height="745px" /></a>

### With height + max-height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" max-height="745px" height="700px"/></a>

### With neither
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png"/></a>

