# Use Node.js 14 as the base image
FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Copy all files from the current directory to the working directory
COPY . .

# Install dependencies using yarn
RUN yarn install

# Expose port 5000
EXPOSE 5000

# Command to run the application
CMD ["yarn", "start"]