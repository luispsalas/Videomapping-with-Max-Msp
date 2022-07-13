# Videomapping-with-Max-Msp
Max-Msp patcher that makes use of the 'jit.gl.meshwarp' object to map video clips to either one or two outputs (two jit.world instances).

Up to 6 layers per output can be mapped. It’s thought to be used with light looping video sources,
as simultaneous playback of many videos will be intensive on processing resources. 

See https://www.youtube.com/watch?v=DAyjdwEoKm4 for extra information on the jit.gl.meshwarp object.





CONTROLS:

'start' = Start playback on layer.

'stop' = Stop playback on layer. 

'enable $1' = Enable specific layer (May cover lower layers if enabled without source).

'show_ui $1' = Show wireframe. 

'read' = Select layer video source file.

'write' = Save mapping on layer (JSON dict. See more on object docs).

Layer Order =  (3 = Uppest layer) / (-2 = Lowest layer)


***Double click on jit.gl.meshwarp objects for extra layer attributes***
