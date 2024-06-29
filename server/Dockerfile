FROM node:18

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install the dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Make port 5000 available to the world outside this container
EXPOSE 5000

# Define environment variable
ENV DATABASE_URL="mongodb+srv://ayc03:YCXVP05RSJ1EGH2a@cluster0.fp9iisi.mongodb.net/StudyNotionDB"
ENV PORT=4000

ENV MAIL_HOST=smtp.gmail.com
ENV MAIL_USER=adityachaudhari750@gmail.com
ENV MAIL_PASS=wvntgxekpkedniuc

ENV JWT_SECRET="adityachaudhari"

ENV FOLDER_NAME="StudyNotion-ByAditya"  
ENV CLOUD_NAME=dgmkbeuic
ENV API_KEY=957528748953495
ENV API_SECRET=jwrIwxZULiztZCz7Jz6up37EVaI  

ENV RAZORPAY_KEY=rzp_test_N4Ogfx9jTrW8BF
ENV RAZORPAY_SECRET=qrQcKlJu7vVxTW0t00dUAx4t
ENV NODE_ENV=production

# Run the application
CMD ["npm", "start"]
