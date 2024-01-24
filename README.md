# How to install Git on macOS and integrate it with your Visual Studio Code editor

## Instructions:

1. **Open terminal on Mac:**
   - On your Mac, do the following: Click the Launchpad icon in the Dock and type 
   ```bat
        terminal
   ```
    in the search field, then click on terminal.

2. **Install Xcode in terminal:**
    - Enter the following command in the terminal
    ```bat
        xcode-select --install
    ````
    - Click OK when installation done


3. **Open Visual Studio Code editor:**
    - Click on the Extensions icon 

    
4. **Install Extensions Packages for Github:**
    - Search for 'GitHub Pull Requests and Issues'
    - Install extension
    - Search for 'GitHub Repositories'
    - Install extension
    - Search for 'GitHub Codespaces'
    - Install extension


5. **Close Folder**
    - Click on File on the Menu in Visual Studio Code and then click on - 'Close Folder'
  
6. **Create a new folder and a html file:**
    - Next click on File on the Menu in Visual Studio Code and clik on - 'New File'
    - Enter - 'index.html' in the little popup window and click then on the 'Enter' keystroke
    - A new window popups - create now a new folder named - 'testrepo' and save your 'index.html' into it

7. **Insert default HTML Code into the index.html**
    - Use shortcuts from 'emmet' to create a default index.html website.
    - Save the file

8. **Close index.html File**
    - Close your current index.html file by clicking on the 'x' icon on the tab

9. **Open the Folder testrepo**
    - Go to File in the Menu and click on - 'Open Folder' and choose the folder - 'testrepo'

10. **Click on the Source Control icon**
    - Click on - the 'Source Control' icon in the left menu bar
    - Click on the blue button - 'Initialize repository'
    - Enter the following message 'First commit' in the input field
    - Then click on the blue button - 'Confirm'
    - Next click on the blue button - 'Publish Branch' and choose - ' Publish to public Github public repository'
    - Finally a message will popup saying that - 'The repo was Successfully published to GitHub'.

11. **Open Github.com and check you newly published repo**
    - Login on to your Github.com account
    - Click on your avatar in the top right corner
    - Next click on - 'Your repositories'
    - Check and see if your newly created repo - 'testrepo' is available