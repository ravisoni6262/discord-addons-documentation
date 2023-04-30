# Connecting the ExpressTechSoftWares  Add-ons to the Discord server

This documentation provides  you  with an introduction to the ExpressTechSoftWares Discord Add-ons.
It is  intended for website  owners  who  wish to offer  their  users the ability to connect  their  accounts to the Discord server.
The ExpressTechSoftWares  Add-ons  make  it possible to link Discord roles  and:

 - Memberships: if you offer a subscription system ( PMPRO, MemberPress, ...)
 - Courses: if you have installed an LMS ( LearnDash, LearnPres, ...)

The first step  requires  creating a Discord Application and collecting the data necessary to make the Add-ons  work  correctly.

## Step1: New Application

Go to: [https://discord.com/developers/applications](https://discord.com/developers/applications)

![new-app](https://user-images.githubusercontent.com/31171/235369112-51f8366b-5817-4b50-943e-5cf925286ca0.png)

Click on New Application :

![new-app2](https://user-images.githubusercontent.com/31171/235369181-de5e3d93-c093-475a-b8e5-3acd1ea0a79d.png)


Give a relevant name to your application and click on Create .

## Step2: Create the Bot 

Now you will create a Discord Bot, which will be responsible for managing Discord roles for users: assign roles, delete roles... 

Click on the Bot menu: 

![new-app3](https://user-images.githubusercontent.com/31171/235369283-373e273e-9e90-44ab-bb54-793b0b77e8d1.png)

**Copy the Bot Token and save it, we will need it later.**

![new-app4](https://user-images.githubusercontent.com/31171/235369317-dff27566-0f6e-4995-bf95-9bea1e4a7fef.png)

