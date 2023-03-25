# Crypto-beta-analysis
Calculate the Beta value of different tokens on different exchanges, Binance spot, Binance with btc as base pair and Bybit perp.

(I take no repsoncibility for any bugs or errors if you use this script)

Download and install Visual Studio Code:

    Visit the Visual Studio Code website at https://code.visualstudio.com/.
    Download the appropriate installer for your operating system (Windows, macOS, or Linux).
    Run the installer and follow the installation prompts to complete the installation.

Install the Python extension for Visual Studio Code:

    Open Visual Studio Code.
    Click on the Extensions icon on the left sidebar or press Ctrl+Shift+X.
    Search for "Python" in the search bar.
    Click the "Install" button on the official Python extension by Microsoft.

Set up the project folder:

    Extract the provided folder containing the scripts for different exchanges and trading pairs.
    Open Visual Studio Code.
    Click "File" > "Open Folder" and select the extracted folder.
    The folder should now appear in the Explorer panel on the left side of Visual Studio Code.

Install the required Python packages:

    Click on the "Terminal" menu and then click on "New Terminal".
    In the terminal, type the following command and press Enter to install the required packages:

        pip install ccxt pandas numpy

    Run the script:
        In the Explorer panel, navigate to the folder containing the script you want to run (e.g., "Bybit perpetual").
        Right-click on the script file (e.g., "downloader.py") and click "Run Python File in Terminal".
        The script will start running, and you'll see the output in the Terminal panel.

    View the output:
        Once the script has finished running, you'll find a file named "token_beta_data.json" in the same folder as the script.
        You can open this file in Visual Studio Code to view the output.

    Run a simple web server to serve the webpage:
        Install the "Live Server" extension in Visual Studio Code:
            Click on the Extensions icon on the left sidebar or press Ctrl+Shift+X.
            Search for "Live Server" in the search bar.
            Click the "Install" button on the "Live Server" extension by Ritwick Dey.
        Create an index.html file in your project folder or use the provided one.
        Right-click on the index.html file and select "Open with Live Server".
        Your default web browser will open, and you can view the webpage.

Remember to replace the file and folder names in these instructions with the appropriate names for your specific project.
