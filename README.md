
# WhatsApp App for Linux

A simple Electron-based application to run WhatsApp Web on Linux as a desktop application.

## Features
- Runs WhatsApp Web in a standalone app
- Built using Electron
- Available in *AppImage* format for Linux

## Requirements
Before you can build and run the application, make sure you have the following installed:
- **Node.js** and **npm**

## Installation and Setup

### Step 1: Clone the Repository
First, clone this repository to your local machine:

```bash
git clone https://github.com/bimacloud/Whatsapp_app_linux.git
cd Whatsapp_app_linux
```

### Step 2: Install Dependencies
Install the necessary dependencies using npm:

```bash
npm install
```

This will download and install all the required Node.js modules for the project.

### Step 3: Build the Application
To build the application into an *AppImage* format, run the following command:

```bash
npm run build
```

After the build process is completed, you will find the output in the `dist/` folder.

### Step 4: Run the Application
To run the application, give the *AppImage* executable permissions and then execute it:

```bash
chmod +x Whatsapp_app_linux/whatsapp-app-1.0.0.AppImage
./Whatsapp_app_linux/whatsapp-app-1.0.0.AppImage
```

You can also run the app by double-clicking the *AppImage* file.

## Running in Development Mode

If you want to run the app without building, you can run it directly in development mode using:

```bash
npm start
```

This will open the app in a development window using Electron.

## Contributing
Feel free to submit issues or pull requests. Contributions are always welcome!

## License
This project is licensed under the ISC License.
