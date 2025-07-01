## Connecting to EC2 for Active Directory Configuration

### Objective

This SOP outlines the steps to connect to an EC2 instance for configuring Active Directory.

### Key Steps

 

**Step 1: Access EC2 Instance** [0:07](https://loom.com/share/bbefb6bf15a0454199926c67cafbfd64?t=7)

![generated-image-at-00:00:07](https://loom.com/i/000d5bc385ba437bbfd152e5371e5370?workflows_screenshot=true)

- Navigate to the EC2 dashboard.
- Select the instance you want to connect to.
- Click on 'Actions' and then select 'Connect'.

 

**Step 2: Download Remote Desktop File** [0:16](https://loom.com/share/bbefb6bf15a0454199926c67cafbfd64?t=16)

![generated-image-at-00:00:16](https://loom.com/i/3a697bcb8dc0440d9e141768806000f4?workflows_screenshot=true)

- In the connection options, choose 'RDP client'.
- Click on 'Download remote desktop file'.

 

**Step 3: Connect to the Instance** [0:26](https://loom.com/share/bbefb6bf15a0454199926c67cafbfd64?t=26)

![generated-image-at-00:00:26](https://loom.com/i/2bdce4f1a4bd4dd5b4d757afa17a84ab?workflows_screenshot=true)

- Open the downloaded remote desktop file.
- When prompted, enter the password.

 

**Step 4: Retrieve Password Using Key** [0:35](https://loom.com/share/bbefb6bf15a0454199926c67cafbfd64?t=35)

![generated-image-at-00:00:35](https://loom.com/i/96f826b1d531471e84f0d3a54dfcb9f5?workflows_screenshot=true)

- Use the private key associated with your instance to decrypt the password.
- Ensure you have the correct key file (e.g., 'My Windows test').

 

**Step 5: Confirm Connection** [0:53](https://loom.com/share/bbefb6bf15a0454199926c67cafbfd64?t=53)

![generated-image-at-00:00:53](https://loom.com/i/8149206b40404595afcfd3f75c54ab72?workflows_screenshot=true)

- After entering the password, click 'Yes' to confirm any security prompts.
- Wait for the connection to establish.

 

**Step 6: Launch Windows Virtual Machine** [1:08](https://loom.com/share/bbefb6bf15a0454199926c67cafbfd64?t=68)

![generated-image-at-00:01:08](https://loom.com/i/3b88e79b407c4a879859ffb0cdea854b?workflows_screenshot=true)

- Once connected, you will have successfully launched the Windows virtual machine.

### Cautionary Notes

- Ensure that your security group settings allow RDP access (port 3389).
- Keep your private key secure and do not share it with unauthorized users.

### Tips for Efficiency

- Familiarize yourself with the EC2 dashboard to quickly navigate to instances.
- Keep the private key file easily accessible to avoid delays in retrieving the password.

### Link to Loom

<https://loom.com/share/bbefb6bf15a0454199926c67cafbfd64>
