# Build a .NET console application using Microsoft Graph

In this demo you will create a .NET console application from scratch using .NET Framework 4.7.0, the Microsoft Graph SDK, and the Microsoft Authentication Library (MSAL).

> The final results of this demo can be found in the SharePoint Github organization within the **sp-dev-fx-webparts** repo: [Display List JavaScript Client-Side Web Part](https://github.com/SharePoint/sp-dev-fx-webparts/tree/master/samples/js-display-list)
> 
> The following steps detail detail how to obtain a copy and run the sample solution for the demo.

## Clone the demo solution

1. Open a command prompt and navigate to a folder where you can put the demo.
1. Clone the **sp-dev-fx-webparts** public repository:

    ```bash
    git clone https://github.com/SharePoint/sp-dev-fx-webparts.git
    ```

1. Change directory to the location of the **Display List JavaScript Client-Side Web Part** sample, located in the **./samples/js-display-list** folder:

    ```bash
    cd samples/js-display-list
    ```

1. Download / install all the project dependencies:

    ```bash
    npm install
    ```

1. Run the demo by starting the web server

    ```bash
    gulp serve
    ```

1. The gulp **serve** task will launch a browser with your local workbench loaded.

    Select the **+** in the middle of the page and add the web part to the page

    > include additional steps on how it works