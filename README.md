# RTSP source DirectShow filter for Windows
  RTSP Player is a very simple IP camera veiwer . 
  Fast application to playback network stream from IP cameras, video servers and surveillance systems. 

Supported types of streaming: RTSP, RTP, UDP (Multicast stream support)

Usage:

1) Registry

  regsvr32 RTSP_source.ax
  
2) Add RTSP source filter to DirectShow Graph

  Select RTSP source filter from list
   
  Click Insert button

![RTSP player sample1](http://www.videoexpertsgroup.com/git/rtsp.source.add.to.graph.png)

3) Change setting of RTSP source filter

  Set IP address
  
  Select needed protocol Important note: unselect/select protocol even if needed protocol is switched on
  
  Click Apply and OK buttons

![RTSP player sample1](http://www.videoexpertsgroup.com/git/rtsp.source.change.settings.png)

4) Connect graph

  Select output pin and select Render Pin or connect Graph manually 

![RTSP player sample1](http://www.videoexpertsgroup.com/git/rtsp.source.connect.graph.png)
  
5) Play graph

  Click Play button  

![RTSP player sample1](http://www.videoexpertsgroup.com/git/rtsp.source.play.graph.png)
 


