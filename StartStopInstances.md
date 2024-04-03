# Start And Stop EC2 Instance
## Start the instance
1. Login to the AWS Console as Bedrock user and select EC2.
2. Start the instance named `my-llm-lc-vm-0-nvidia-gpu`
3. Login to this instance via SSH (or connect via EC2 instance connect).
4. Once terminal is accessible on the instance cd into folder
   ```bash
   $ cd ~\pdfChatBot
   ```
6. Activate the python virtualenv by the following command
   ```bash
   $ source \env\Scripts\activate
   ```
   Post the the command prompt would change as shown below:
   ```bash
   (env) $
   ```
8. Start the Streamlit server by the below command:
   ```bash
   $ streamlit run app.py
   ```
9. This should launch the application and show the internal and external IPs of the application like so:
   ```bash
     You can now view your Streamlit app in your browser.

   Network URL: http://10.0.0.255:8501
   External URL: http://52.201.251.198:8501
   ```
   Navigate to the External URL shown in the output above to access the app.
   PS: The External URL is transient in nature and changes from time to time when the EC2 instance is restarted.

## Stop the EC2 Instance
1. Login to the AWS Console as Bedrock user and select EC2.
2. Stop the instance named `my-llm-lc-vm-0-nvidia-gpu`
