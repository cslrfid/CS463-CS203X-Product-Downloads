# CS463/CS203X Product Information

You can find the following information in this repository:

1. **User's Manual**
<br><br>
CSL Intelligence Reader User's Manaual
<br><br>
2. **CSL Unified API**
<br><br>
This full-featured Software Development Kit (SDK) is based on Micrsoft .NET Framework and written in native C#.  The CSLibrary.dll file can be imported into your existing .NET based application for enabling RFID tag access in a short time.
<br><br>
In order to enable this Unified API, you will need to go to **System** -> **Access Mode** on the web interface and select ```CSL Unified API/High Level```.
<br><br>
Under this access mode, the reader is expected to be fully controlled by the PC running the associated library and software.
<br><br>
3. **CSL HTTP API**
<br><br>
Under this access mode, you are expecting reader will be running automonously with with its built-in event engine.
<br><br>
For more information on the event engine, you can refer to the [user's manual](https://github.com/cslrfid/CS463-CS203X-Product-Downloads/tree/main/Manuals/1%20-%20User%20Manual) or the [following article](https://cslrfid.github.io/2020-03-26-cs463-getting-started/).
<br><br>
In order to enable CSL HTTP API, you will need to go to **System** -> **Access Mode** on the web interface and select ```HTTP/XML```.
<br><br>
Under this access mode, the reader is expected to be running automonously and you can send out command through HTTP POST for any changes to the configurations, where the reader will reppond with messages in XML.
<br><br>
4. **TCP/IP Network Specifications**
<br><br>
If you are interested in building your own driver for communicating with the reader, the low-level messaging protocol is documented on the network specification document.  However, this method of access is only recommended for advanced users who are interested in building the software by sending direct TCP/UDP messages to the reader.



