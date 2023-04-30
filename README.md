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


Give a relevant name to your application and click on Create .![new-app7](https://user-images.githubusercontent.com/31171/235369751-c2901bbf-d34a-4e75-9257-9ab3231edd70.png)


## Step2: Create the Bot 

Now you will create a Discord Bot, which will be responsible for managing Discord roles for users: assign roles, delete roles... 

Click on the Bot menu: 

![new-app3](https://user-images.githubusercontent.com/31171/235369283-373e273e-9e90-44ab-bb54-793b0b77e8d1.png)

**Copy the Bot Token and save it, we will need it later.**

![new-app4](https://user-images.githubusercontent.com/31171/235369317-dff27566-0f6e-4995-bf95-9bea1e4a7fef.png)

## Step3: Client ID and Client Secret 

![new-app5](https://user-images.githubusercontent.com/31171/235369616-c4a85bf4-84b5-478e-9c47-4ca2bfd32523.png)

Copy the Client ID and the Client Secret and save them as you did for the Bot Token. 

## Step4: Server ID 

To have the server ID, First You will activate the developer mode. 

Click on the “User Settings” gear in the bottom left of the screen:  


![new-app6](https://user-images.githubusercontent.com/31171/235369733-d693c3db-f4f1-4a1e-a087-941928f215d3.png)

![new-app7](https://user-images.githubusercontent.com/31171/235369788-2c0be4d7-21c6-4545-9406-3a10aa4313f2.png)

![new-app8](https://user-images.githubusercontent.com/31171/235369798-c515b8b0-2144-40d9-8c3f-39431d03017b.png)

 

Now click on the server icon in the left-hand side of discord.com screen and copy the server ID : 

![new-app9](https://user-images.githubusercontent.com/31171/235369847-9bd724c4-615e-4394-8d5f-a29dc30111db.png)

## Step5: Connect the BOT 

All Discord add-ons have the same user interface. 

After installing and activating an Add-On, you will have a submenu: Discord Settings. 

in this example we will take LearnDash LMS as an example : 

![new-app10](https://user-images.githubusercontent.com/31171/235369891-b7a0cfac-4b99-4ea3-b3c4-9c43755a5f30.png)

Now you fill in the form with the data saved before: Client ID, Secret ID, Bot Token, Server ID.

Also, you need to copy/paste the URLs: :

- Redirect URL. 
- Admin Redirect URL Connect to bot 


![new-app11](https://user-images.githubusercontent.com/31171/235370053-912019a9-94a7-40cd-b5dd-d5196bf09570.png)

Click ‘Save Settings’. 
After clicking on 'Save Settings', and if you have followed the steps correctly, you will have a new button that appears that you are invited to connect the Bot :


![new-app13](https://user-images.githubusercontent.com/31171/235370270-424f73af-57cd-43c9-bdb5-d5e62a1b441b.png)

You also noticed the appearance of a new sentence:  
**Make sure the Bot ExpressTechSoftWares App BOThave the high priority than the roles it has to manage. Open DiscordServer.**
Of course, the sentence contains the name of your Bot you named. 

Now click on the red button 'Connect your Bot'. you will be redirected to Discord authentication : 

![new-app14](https://user-images.githubusercontent.com/31171/235370345-f02225d3-7e21-4b1f-84cf-c912de455836.png)

Click Authorize. 

You will be redirected to the Admin page. 

Congratulations ! you have successfully connected the bot: 

![new-app15](https://user-images.githubusercontent.com/31171/235370379-d7ae9e98-41a2-4bb2-83ec-482ad79c48ce.png)

Also, you will be notified of the arrival of the Bot : 

![new-app16](https://user-images.githubusercontent.com/31171/235370391-2cc92ba8-980c-408c-97eb-d6fb29f3f84f.png)

##Step6: Give Bot High Priority 
For the Bot to handle roles, it must have high priority. 
Go to Server Settings

![new-app17](https://user-images.githubusercontent.com/31171/235370568-812a7f15-38f1-43f1-956c-00c391b04d94.png)

Drag & Drop Bot on top of all Roles  and save changes: 


![new-app18](https://user-images.githubusercontent.com/31171/235370577-43bf8b43-912a-424d-b0f1-949f45568ea1.png)

To verify that the add-on works as expected, go to: Role Mappings. 

you should see the discord roles: 

![new-app20](https://user-images.githubusercontent.com/31171/235370615-ce75e142-9d51-4c22-8001-1c7843575eb1.png)
