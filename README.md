# Tchat-Itta-SignalR MVC 5 
=======

Installation SignalR
============

Open the Tools | Library Package Manager | Package Manager Console and run the following command. This step adds to the project a set of script files and assembly references that enable SignalR functionality.

    install-package Microsoft.AspNet.SignalR

In Solution Explorer, expand the Scripts folder. Note that script libraries for SignalR have been added to the project.

    php composer.phar update

In Solution Explorer, right-click the project, select Add | New Folder, and add a new folder named Hubs.

Right-click the Hubs folder, click Add | New Item, select the Visual C# | Web | SignalR node in the Installed pane, select SignalR Hub Class (v2) from the center pane, and create a new hub named ChatHub.cs. You will use this class as a SignalR server hub that sends messages to all clients.

    Clients.All.addNewMessageToPage(name, message);

Owner:
- Nordine

