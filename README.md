# Plagiarism-Detector Program
The program is expected to take in 2 text files, and look for similarities between the 2 of them. The present goal of this project is to detect the degree of absolute matching between the 2 text files.

Visit the [Wiki](https://github.com/ABusyProgrammer/PlagiarismDetector/wiki "Project Wiki") for more background on the project.

# Setup and Installation
To run this project on your computer, you will need the following installed:
1. Java SE Development Kit
2. Git

## Check Installation
To check if your Java installation was successful, run the following command:
```
java -version
```
This should print out the version number of the Java installation. Then run:
```
javac -version
```
This will output the version of the Java compiler if it is successfully installed.

To check if Git is installed successfully:
```
git --version
```
This should output the git version installed.

## Installation
You can install this project by following these steps:
1. Open the git command line, and change into the directory you want to save this project in.
2. Run the following command to get the repository in that folder:
```
git clone https://github.com/ABusyProgrammer/PlagiarismDetector
```
3. Change directory into the project folder, and into `/src/`
4. Run the following command (*optionally you can provide your own original-textfiles directory and plagiarized-textfiles directory in full-address. Don't add any parameters if you just want to use test the program on the files in this repository itself*):
```
javac Test.java
java Test [original_directory] [plagiarized_text_directory]
```
5. Open the `output.csv` file after it is done running.

### Notes
If you are using an IDE to run the program, then the directories specified under `Test.java` may have to be edited, since directories often read directories differently.
* For IntelliJ, add `src/` in front of every directory specified in `Test.java`

Most IDEs will guide you through the setup of the project; IntelliJ will automatically create a .idea workspace. You only have to follow through the Project cretion in your respective IDE.
