# qml_demon
qml-qquick capture cameras to gstreamer1.0,to qt render Demon.Using appsink/appsrc and imx plugins to convert YUV->RGBA.  
We use qml-qquick 2 GstGLVideoItem to display two cameras(camera0+camera1).   
gstreamer1.0 to capture camera1,and convert YUV->RGBA to qmlglsink.  
gstreamer1.0 to capture camera0(IRD camera) using appsink/appsrc to producc data, and to qmlglsink to qt.  
[Descs]  
     Qml demons to display two cameras.  
     Using imx codec,so cpu using is low...  
[src codes]  
QQ:420788046  
Email:luwei860123@163.com  

