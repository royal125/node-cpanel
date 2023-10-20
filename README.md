curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

# Reload your shell to use nvm
source ~/.bashrc

# Install a specific Node.js version (e.g., Node.js 14 LTS)
nvm install 14

# Set Node.js version as default
nvm alias default 14


node -v 
npm -v
5. Install PM2 (Optional, but recommended for running Node.js applications

npm install -g pm2
6. Set Up Node.js Applications:

Upload your Node.js application to your server, and use PM2 to manage your application's lifecycle. Here's how you can start a Node.js application using PM2:

# Change to your app directory
cd /path/to/your/app

# Start your Node.js app
pm2 start your-app.js

cd public_html/sb.aseriujh-pechk.sa.com
