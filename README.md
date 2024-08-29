# Visual Studio Code Configuration and Extensions 

This repository contains a personal configuration setup for Visual Studio Code. 

## Installation Instructions

### 1. Install Visual Studio Code

If you haven't already, download and install Visual Studio Code from the official website: [Download Visual Studio Code](https://code.visualstudio.com/).

### 2. Clone the Repository

Clone this repository to your local machine:

```
bash
git clone https://github.com/OroCap/VisualStudioCodeSettings.git
cd VisualStudioCodeSettings
```

### 3. Install Extensions

A list of recommended extensions is provided in the extensions.txt file. To install all the extensions listed:

1. Open Visual Studio Code.
2. Open a terminal in the root directory of this repository.
3. Run the following command to install all the extensions:
```
bash
cat extensions.txt | xargs -n 1 code --install-extension
``` 

This command will iterate through the extensions.txt file and install each extension listed.

### 4. Configure Visual Studio Code

To apply the settings included in this repository:

1. Navigate to the settings directory in Visual Studio Code:
   - *Windows:* C:\Users\<your-username>\AppData\Roaming\Code\User\
   - *macOS:* ~/Library/Application Support/Code/User/
   - *Linux:* ~/.config/Code/User/
2. Copy the settings.json file from this repository to the User directory mentioned above, replacing the existing one if prompted.

### 5. Restart Visual Studio Code

After applying the settings and installing the extensions, restart Visual Studio Code to ensure all changes take effect.

##### Enjoy your enhanced Visual Studio Code setup! 