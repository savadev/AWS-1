# How do I transfer an Amazon EC2 instance to a different AWS account?

 ### Step: 1  Create an instance in the Source account -->> Upload some files for testing (whether the same comes to the destination account)

 ### Step :2  Create an AMI from the above instance in the source -->> Add Destination AWS account number to the Permission tab in the particular AMI

 ### Step :3 Based on the Destination AWS account number ,the AMI which we created in the source will replicated in the destination account under Images -->> AMI

 ### Step :4 Create an Instance in the destination account by selecting the AMI which created automatically

 ### Step :5 We can now see the files which we created in the source account instance (if we add the same ENI which we added to the source image for storage,then add any                data in that instance from that image.so that the same data will replicated to the newly created Image) 



