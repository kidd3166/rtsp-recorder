*Rtsp packet recorder (without transcoding)*

Originally by @d-a-gerashenko

**Usage** 

`Device device = new Device ( ... );`
`device.triggerRecording(true,RecordInvoker.TYPE.ALWAYS);` starts the recording.
 `device.triggerRecording(false,RecordInvoker.TYPE.ALWAYS);`stops the recording.


