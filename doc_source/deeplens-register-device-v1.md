# Register Your AWS DeepLens Device<a name="deeplens-register-device-v1"></a>

The instructions presented thereafter apply to the original \(also known as v1\) AWS DeepLens device\. You can find out the hardware version at the bottom of your AWS DeepLens device\. If you don't see **HW v1\.1** printed there, your device is of the original AWS DeepLens edition\. You can then proceed as instructed as follows\. Otherwise, see [Register AWS DeepLens 2019 Edition Device](deeplens-register-device-v1.1.md)\.

The registration process involves performing the following tasks\. Some of the tasks are carried out on the AWS Cloud and others are on the AWS DeepLens device\.
+ Name your device so that you can identify it within the AWS DeepLens service\. 
+ Grant IAM permissions to build and deploy AWS DeepLens projects for deep learning computer vision applications\. 
+ Download a security certificate for the device\. This certificate is generated by AWS IoT upon request by the AWS DeepLens service\. You must upload it to the device when setting up the device later\.
+ Create an AWS IoT thing representation for your AWS DeepLens device, which is carried out by AWS IoT Greengrass upon request by the AWS DeepLens service\.
+ Turn on the device's setup mode and join your computer in the device's local Wi\-Fi \(also referred to as `AMDC-NNNN`\) network\. This lets you call the device setup app as a web application hosted by the local web server of the device\.
+ Start the device setup application on the device to configure device access to internet; to upload the AWS\-generated security certificate to the device for the AWS Cloud to authenticate the device; and to create a device login password for signing in to the device using a hardwired monitor, mouse and keyboard or using an SSH client from a computer within the same home or office network\.

Your AWS DeepLens device has a default password of `aws_cam`\. You can use this default device password to log on to the device connected to a monitor using a *μ*USB\-to\-USB cable, a USB mouse and possibly a USB keyboard even before registration\. For security reasons, you should reset this password with a more complex or strong password phrase\.

**Topics**
+ [Configure Your AWS Account for AWS DeepLens Device](deeplens-start-registering-device-using-console.md)
+ [Connect to Your AWS DeepLens Device's Wi\-Fi Network](deeplens-getting-started-connect.md)
+ [Set Up Your AWS DeepLens Device](deeplens-getting-started-set-up.md)
+ [Verify Your AWS DeepLens Device Registration Status](deeplens-getting-started-verify-connection.md)