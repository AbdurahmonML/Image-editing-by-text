# Telegram Image Modifier Bot

This Telegram bot allows users to modify images based on text descriptions provided by the user. It uses an AI model to interpret the text and apply modifications to the images accordingly.

## Why This Bot is Useful

This bot allows users to easily modify images using simple text descriptions, making image editing more accessible and intuitive without needing specialized software or skills. It streamlines the process of creating custom images for personal or professional use.

## Features

- **Modify Existing Images**: Users can upload a real image or they can use randomly generated image by bot and provide a text description of the changes they want to make.
- **Interactive and Easy to Use**: The bot guides users through the process of uploading images and describing desired modifications.

## Used models

- **Model e4e for encoding real image**
- **Stylegan2 for generating images from vector**
- **CLIP for measuring loss between image and text**

## Bot Commands

- `/start` - Welcome message and basic instructions.
- `/random` - Bot generates random image.
- `/upload_image` - User uploads real image, with this comand bot will understand it.


