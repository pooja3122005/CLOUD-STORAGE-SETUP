# CLOUD-STORAGE-SETUP
**COMPANY**:CODTECH IT SOLUTIONS

**NAME**: POOJA.U

**INTERN ID**:CT04DG1131

**DOMAIN**: CLOUD COMPUTING

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTOSH

##DESCRIPTION
Setting up and configuring cloud storage on Amazon Web Services (AWS) Simple Storage Service (S3) provides a reliable and scalable solution for storing data in the cloud. For this setup, a bucket named my-aws-pooja-01 was created as a dedicated storage container for uploading, managing, and sharing files over the web. S3 is widely used due to its durability, ease of access, integration with other AWS services, and flexible permission controls.

The process began by accessing the AWS Management Console and navigating to the S3 service, where the bucket was created. The bucket name my-aws-pooja-01 is globally unique, as required by AWS, ensuring that it does not conflict with any existing S3 buckets worldwide. The bucket was created in the us-east-1 region, although this can vary depending on data residency or performance needs. The default settings for versioning, encryption, and logging were initially left unchanged, although these features can later be enabled to enhance security, data recovery, and auditing.

After successfully creating the bucket, a few example files were uploaded to demonstrate the bucket’s functionality. These included different file types such as text documents, images, and PDFs to represent a variety of content that might typically be stored in S3. Uploading files through the AWS Console is simple and user-friendly, allowing users to drag and drop files or select them directly from the local file system. During the upload process, storage class and encryption settings can be selected; the default "Standard" storage class was used, which is ideal for frequently accessed data.

Once the files were uploaded, the next critical step was to configure the bucket’s access permissions. S3 provides a powerful and flexible set of access management options, including bucket policies, IAM roles and policies, access control lists (ACLs), and object-level permissions. For this setup, a basic bucket policy was added to grant public read access to all objects within the bucket. This is especially useful for publicly hosted assets such as images or downloadable resources in a test or demonstration environment. The policy included permissions that allow any user to read files using HTTP GET requests.

It is important to note that while public access was enabled in this scenario for the purpose of demonstration, AWS best practices recommend keeping buckets private unless there is a specific need for public availability. Misconfigurations can lead to sensitive data exposure, so care must be taken to review and monitor access settings regularly. AWS also provides tools such as S3 Access Analyzer and Bucket Policy Editor to help users manage and audit permissions more effectively.

To validate the setup, object URLs were used to access the uploaded files through a web browser. These URLs point directly to the files stored in the S3 bucket and can be shared or embedded in web applications. The ability to access the files confirmed that the bucket was correctly configured and the permissions were working as intended. For programmatic access, AWS CLI or SDKs (e.g., Python Boto3) can be used to interact with the S3 bucket, offering automation and integration with larger cloud-based systems.

Overall, the configuration of the my-aws-pooja-01 bucket on AWS S3 demonstrates a complete cloud storage setup, ready for a wide range of applications, from simple file sharing to hosting static assets for web platforms.




