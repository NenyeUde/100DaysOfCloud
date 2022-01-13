
# IAM - Identity Access Management (IAM Users, Groups, Policies)

## Introduction

IAM is useed to control who is signed in and has permissions to use resources(Authentication and Authorization). When you create your AWS account, you start with the root user account that has automatic access to all AWS services but, it isn't best practice to use this root user for daily tasks. Rather, create an IAM user with the root user account. With IAM you can securely control access to AWS services and resources for users in your AWS account.

## Users, Groups and Policies 

IAM Users - Each IAM User can represent one person in your organization. They can be assigned permissions (we"ll get to that) you can create individual IAM users within your account that correspond to users in your organization. IAM users are not separate accounts; they are users within your account. IAM Users can also be grouped together.

IAM Groups - Simply put, this is a group of IAM Users. When permissions are assigned to a group, all Users in that group get that permission too. It is important to note which users you add to a group and what permissions are granted to them. Groups only contain Users, you can not create a group inside a group but a user can belong in more than one group.

IAM Policies - Access management can be done by creating policies and attaching them to IAM identities or AWS resources. Policies are JSON documents that, when attached to an identity or resource, define their permissions. Basically, it is what a user or a group is allowed to do. This is important cause it helps to save cost, cause users are only allowed to do what they need to do. 



## Try yourself

- Create a user and give them AdministratorAccess
- Create multiple users and add them to a group. Grant them only S3ReadAccessonly
- Create an IAM Policy 


## ☁️ Cloud Outcome

You dont want to lose that document that contains the access ID and secret access key to get into your IAM user account, so make sure to download that document and keepn safe and secure.

## Next Steps

I might want to play around EC2 Instances next. 

