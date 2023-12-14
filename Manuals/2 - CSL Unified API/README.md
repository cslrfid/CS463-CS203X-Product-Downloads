# CS463/CS203X Unified API in C#.NET

In order to get started on developing your own software with the CSL unified API, you can refer to the following two repositories:


1. [**CSL Callback-based Unified API and Demo App (C#.NET)**](https://github.com/cslrfid/CS463-203X-468XJ-PC-Callback-Unified-SDK-App)
<br><br>
This is the complete demo application that demonstrates all features of the APIs with full source code.
<br><br>
If you are starting your development from scratch, you can consider taking the demo app as your base and add new features on top.  For instance, you can use the existing inventory page for reading RFID tags.  You might just need to have an additional button on the page for triggering a hook to the WebAPI or procedure that stores the captured data.
<br><br>
[**CSL Unified API Documentation**](./CSLibrary-Documentation)
<br><br>
2. [**CSL Multi-Reader Simple Demno App**](https://github.com/cslrfid/CSL-Multireader-Simple-Demo)
<br><br>
This is a simple console application that illustrate the easiest way for calling the APIs on the CSLibrary.
<br><br>
After adding reference to the CSLibrary .NET assembly on the Visual Studio project, you can create an instance of the HighLevelInterface and perform different RFID operations.
<br><br>
You will also be able to create mulitple instances for capturing RFID data from mulitple readers at the same time.
<br><br>
This code example is recommended for developers who are starting with an existing .NET-based application and would like to add RFID features on top.