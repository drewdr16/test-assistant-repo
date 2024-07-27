# Test Assistant Repo

## Table of Contents
- [Description](#description)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

Title:  First Test Assignment for Virtual Assistant/Junior Project Manager at Ellty

This is a test repository to verify and evaluate the skills and ability of an aspiring assitant of Ellty to use Git, VSCode, and Markdown. The contents of this repository includes installation instructions of cloning respositories, dependencies and how to run the project locally. The repository also includes; a description to start a React Application, and outline guidelines for repository contributors. 

## Installation Instructions

    1. Create a new repository in GitHub. To create one simply the NEW Button in the GitHub Dashboard.
    2. Assign a Repository name. In this case I used test-assistant-repo and made it Public as instructed.
    3. Before clicking the Create Repository, initialized it first by adding a readme.md file.
        3.1 If you forgot to add the readme file you can use other software/apps to create one. 
            3.1.1 I used VSCode and created a file there by clicking the Ctrl + N.
            3.1.2 After working on the readme file. Save it as a markdown file. Doing so would add the file extension .md beside readme.
    4. Click Create Repository and you will be redirected again in the dashboard.
    5. Click test-assistant-repo to view your newly created repository.

1. Clone the repository:
    ```sh
    1. After viewing your repository, you can now click the CODE button  to copy the clone url.
    2. Click the copy button.
    
    2 Ways to Clone a Repository

        Through Windows Powershell
                1. Change the directory to your Desktop folder.
                    1.1 Type in: 
                    ```sh
                        cd ~\Desktop
                    ```
                        1.1.1 Possible Problem: Missing Desktop Directory
                            You may proceed to Step 2 IF you didnt encounter any problem. But If you encountered a problem saying it cannot find the path because it doesnt exist. It is probably because you dont have a Desktop Directory.
                        1.1.2 To add it simply type in
                        ```sh 
                            New-Item -Path ~\Desktop -ItemType Directory
                        ```
                        1.1.3 After this try to type in:
                        ```sh
                            cd ~\Desktop
                        ``` 
                        After doing this, it should now work.

                2. Then to create the clone, type in:
                    ```sh
                        git clone <https://github.com/YOUR_USERNAME/test-assistant-repo.git>
                    ```
                    2.1 If you encountered a problem saying "The term 'git' is not recognized as a name of a cmdlet, function, script file, or executable program." Try this, if not, proceed to step 3:
                        2.1.1  Click windows logo and search environment variables.
                        2.1.2  Go to Advanced then click the environment variables button at the bottom.
                        2.1.3  Under System Variables click Path then click the edit button.
                        2.1.4 Now go to file explorer and copy the path where the git.exe file can be found. (e.g. C:\Program Files\Git\bin)
                        2.1.5 Go back to the edit environment variable then click the New Button. Paste the path you copied earlier then click OK.

                3. Go to your Desktop and you can now see your repository folder. Inside it you can see your readme.md file that you initialized earlier.

        B. Through Git Bash
            1. Create Folder in Main Drive
                1.1 Go to your main drive in file explorer and create a folder. In my case a named it SampleGit.
            2. Open Git Bash app and type in
            ```sh
                cd "C:\SampleGit"
            ```
            3. Then to create the clone, type in:
                    ```sh
                        git clone <https://github.com/YOUR_USERNAME/test-assistant-repo.git>
                    ```
            3. Go to your Desktop and you can now see your repository folder. Inside it you can see your readme.md file that you initialized earlier.
    ```
2. Navigate to the repository directory:
    After cloning you need to navigate the repository directory as it is necessary if you will run different commands in the repository. This should be done to point out the correct directory and avoid errors as you go on. with that, type in:

    ```sh
    cd test-assistant-repo
    ```
    After this you can run different commands.

3. Install dependencies:
    To ensure there is no error when making the react app, you should install first the dependencies. As this includes the dependencies required to create and run a react application. With that, type in:

    ```sh
    npm install
    ```

## Usage
    1. After installing dependencies needed, type in to initiate your project with the configuration specified in the package.json file that was installed recently. Type in:
    ```sh
    npm start
    ```

    2. To start the React application, use the following command:
    ```sh
    npx create-react-app "app"
    ```
    You can change "app" to any application name you will come up with.

    3. After installing, check the repository in your file manager and you will see that a new folder has been added containing the name that you have set in the command earlier.

    4. Open the folder using VSCode. File> Open Folder> test-assistant-repo

    5. In VSCode explorer, find the "app" folder, then click the src folder. Here you will see the App.js file which we will use to display a simple "Hello, World!" message.

    6. Just below this code: 
        <div className="App">
       Type in: 
        <h1>Hello, World!</h1>

    7. Go to the terminal by clicking Ctrl + `

    8. Then type in the path of the src folder:
        ```
            cd C:\Users\TDM\Desktop\test-assistant-repo\app\src
        ```
    9. To see the output, write the command:
        ```
        npm start
        ```
    10. You can now see your output on your browser


## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License.
