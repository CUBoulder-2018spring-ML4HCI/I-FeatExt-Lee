# I-FeatExt-Lee

Andrew Lee

Unfortunately I did not have any new devices on hand to test with so I focused on understanding the capabilities of the Wekinator Input Helper so that I'll be able to implement it in future projects.

Tools:
Wekinator<br/>
Processing 3<br/>
Wekinator Input Helper (WIH)<br/>
Dragging a 2d box wekinator example<br/>
Drum beat creator wekinator example<br/>

My system makes it so that a steady beat plays when the box isn't moving and then the beat becomes more intense whenenver the box is moving quickly.  The WIH is actually incredibly useful in filtering user input. When recording examples of the 2d box moving, I would normally have to try and go from "start recording" to draggint he box as quickly as possible in order to minimize the amount of static examples to train the moving box.  However, by changing the threshold so that it only records when the value of velocity changes, I was able to filter out my unwanted examples.  This will end up being extremely useful in smoothing out unwanted noise and picking inputs that I deem useful and significant.

https://github.com/CUBoulder-2018spring-ML4HCI/I-FeatExt-Lee/
