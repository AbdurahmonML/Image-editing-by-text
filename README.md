# Telegram Image Modifier Bot

This Telegram bot allows users to modify images based on text descriptions provided by the user. It uses an AI model to interpret the text and apply modifications to the images accordingly.

## Why This Bot is Useful

This bot allows users to easily modify images using simple text descriptions, making image editing more accessible and intuitive without needing specialized software or skills. It streamlines the process of creating custom images for personal or professional use.

## Articles Read 

I read this paper in order to understand idea behind the solution of this task: https://arxiv.org/pdf/2103.17249

## Features

- **Modify Existing Images**: Users can upload a real image or they can use randomly generated image by bot and provide a text description of the changes they want to make.
- **Interactive and Easy to Use**: The bot guides users through the process of uploading images and describing desired modifications.

## Used models

- **Model e4e for encoding real image**
- **Stylegan2 for generating images from vector**
- **CLIP for measuring loss between image and text**
- **ArcFace for measuring loss between generated image and initial one**

## Bot Commands

- `/start` - Welcome message and basic instructions.
- `/random` - Bot generates random image.
- `/upload_image` - User uploads real image, with this comand bot will understand it.

## How to run the bot

Just run bot_script.ipynb file and import necessary python files from other packages and it will connect to your telegram server (please put your own api token), untill this notebook is running, the bot will continue working.

## Demo

You can see full demo by this link: https://drive.google.com/file/d/1uVZsAG_TaHdp3IG-UKZLVO54KHCGQNb6/view?usp=sharing

![image](https://github.com/user-attachments/assets/5883a8f1-52f1-4764-931a-fb0820d17915)

![image](https://github.com/user-attachments/assets/92f04cba-b62e-4c9f-a0bc-599dfd41bedf)
![image](https://github.com/user-attachments/assets/ed10e572-8808-4ff6-b0cc-2b1cc13f842d)


