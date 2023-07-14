# install-aws-sam-cli-linux

**Linux:**

1. Open a web browser and go to the following URL: https://github.com/aws/aws-sam-cli/releases/latest

2. Scroll down to the "Assets" section and download the latest release of the AWS SAM CLI for Linux. Look for a file with a `.zip` extension.

3. Once the download is complete, open a terminal.

4. In the terminal, navigate to the directory where you downloaded the AWS SAM CLI ZIP file using the `cd` command. For example: `cd /path/to/sam/cli`.

5. Extract the contents of the ZIP file by running the following command: `unzip sam-x.x.x.zip`, replacing `x.x.x` with the version number you downloaded.

6. Change into the extracted directory using the `cd` command. For example: `cd sam-x.x.x`.

7. Run the following command to install the AWS SAM CLI: `sudo ./install`.

8. Verify that the AWS SAM CLI is installed correctly by running the following command: `sam --version`. It should display the version information if the installation was successful.

That's it!