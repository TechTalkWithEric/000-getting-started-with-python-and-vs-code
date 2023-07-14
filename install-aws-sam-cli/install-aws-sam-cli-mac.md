# install-aws-sam-cli-mac

**macOS:**


## Using Brew on macos
If you have brew installed you can quickly install the `aws sam cli``

1. Open a Terminal window on your macOS.

2. Update Homebrew to ensure you have the latest package information by running the following command:

   ```sh
   brew update
   ```

3. Once Homebrew is updated, you can proceed to install the AWS SAM CLI by running the following command:

   ```sh
   brew install aws/tap/aws-sam-cli
   ```

   or

   ```sh
   brew tap aws/tap
   brew install aws-sam-cli
   ```

   This command will initiate the installation process for the AWS SAM CLI using Homebrew.

4. Homebrew will download and install the AWS SAM CLI and its dependencies.

5. Once the installation is complete, you can verify the installation by running the following command:

   ```
   sam --version
   ```

   This command will display the version information of the AWS SAM CLI if the installation was successful.

   Note: If the `sam` command is not recognized, you might need to restart your Terminal window for the changes to take effect.

That's it! You have successfully installed the AWS SAM CLI using Homebrew on your macOS. You can now use the `sam` command to interact with and develop serverless applications using the AWS Serverless Application Model.


## Or Install from Source

1. Open a web browser and go to the following URL: https://github.com/aws/aws-sam-cli/releases/latest

2. Scroll down to the "Assets" section and download the latest release of the AWS SAM CLI for macOS. Look for a file with a `.zip` extension.

3. Once the download is complete, open a Terminal window.

4. In the Terminal, navigate to the directory where you downloaded the AWS SAM CLI ZIP file using the `cd` command. For example: `cd /path/to/sam/cli`.

5. Extract the contents of the ZIP file by running the following command: `unzip sam-x.x.x.zip`, replacing `x.x.x` with the version number you downloaded.

6. Change into the extracted directory using the `cd` command. For example: `cd sam-x.x.x`.

7. Run the following command to install the AWS SAM CLI: `sudo ./install`.

8. Verify that the AWS SAM CLI is installed correctly by running the following command: `sam --version`. It should display the version information if the installation was successful.

