# [Built Portfolio With GitHub ](https://github.com/Rajat-22/Portfolio)

---

# Developer Portfolio

#### Are you struggling to create a professional portfolio website? Look no further! You can use the Developer Portfolio template and create your very own personalized portfolio today! My website is designed to be user-friendly and easily customizable, making it perfect for both developers and freelancers.

---

# Demo :movie_camera:


## View live preview [here](https://rajatsharma-portfolio.vercel.app/).

---

## Table of Contents :scroll:

- [Sections](#sections-bookmark)
- [Demo](#demo-movie_camera)
- [Installation](#installation-arrow_down)
- [Getting Started](#getting-started-dart)
- [Usage](#usage-joystick)
- [Deployment](#deployment-rocket)
- [Packages Used](#packages-used-package)

---

# Sections :bookmark:

- HERO SECTION
- ABOUT ME
- EXPERIENCE
- SKILLS
- PROJECTS
- EDUCATION
- CONTACTS

---

# Installation :arrow_down:

### You will need to download Git and Node to run this project

- [Git](https://git-scm.com/downloads)
- [Node](https://nodejs.org/en/download/)

#### Make sure you have the latest version of both Git and Node on your computer.

```bash
node --version
git --version
```

## <br />

# Getting Started :dart:

### Fork and Clone the repo

To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```bash
git clone https://github.com/<YOUR GITHUB USERNAME>/developer-portfolio.git

cd developer-portfolio
```

### Install packages from the root directory

```bash
npm install
# or
yarn install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

### Running with Docker Compose

1. **Build Docker Image and Run Container**:
    ```bash
    docker-compose up --build
    ```

2. **Access the Application**:
    Visit [http://localhost:3000](http://localhost:3000) in your web browser to view the running application.

---

### Building the Docker Image

1. **Build the Docker Image using Dockerfile.dev**:

    ```bash
    docker build -t nextjs-app -f Dockerfile.dev .
    ```

2. **Running the Docker Container**:

    ```bash
    docker run -p 3000:3000 nextjs-app
    ```

3. **Access the Application**:
    Visit [http://localhost:3000](http://localhost:3000) in your web browser to view the running application.

---

# Usage :joystick:

Please create a new `.env` file from `.env.example` file.

Eg:

```env
NEXT_PUBLIC_GTM =
NEXT_PUBLIC_APP_URL =
TELEGRAM_BOT_TOKEN =
TELEGRAM_CHAT_ID =
GMAIL_PASSKEY =
EMAIL_ADDRESS =
```

### Then, Customize data in the `utils/data` [folder](https://github.com/said7388/developer-portfolio/tree/main/utils/data).

Eg:

```javascript
export const personalData = {
  name: "RAJAT SHARMA",
  profile: '/profile.jpg',
  designation: "Software Developer",
  roles : ['Software Developer', 'Full Stack Developer', 'Software Engineer', 'Web Developer'],
  description: "Hi Everyone, I am RAJAT SHARMA. \n I’m a dedicated Web Developer with a strong passion for crafting intuitive, high-performance web applications. With hands-on experience in modern JavaScript frameworks like React and Vue, I specialize in building responsive, scalable, and user-friendly interfaces that bring ideas to life. \n Whether it's creating a dynamic frontend or collaborating with teams to deliver impactful solutions, I take pride in building with purpose and precision—always pushing to grow, improve, and make a meaningful contribution through technology.",
  email: 'rajatsharma221098@gmail.com',
  phone: '+91-9873957498',
  whatsApp: '+91-9454276383',
  address: 'Greater Noida, India',
  github: 'https://github.com/Rajat-22',
  facebook: 'https://www.facebook.com/profile.php?id=100009971371239',
  linkedIn: 'https://www.linkedin.com/in/rajatsharma22',
  twitter: 'https://twitter.com/_mr_Rajat_?s=09',
  instagram: 'https://www.instagram.com/_mr__sharma__/',
  whatsAppUrl: 'https://wa.me/+919454276383?text=Hello%20I%20want%20to%20connect%20with%20you',
  devUsername: "mrsharma",
  resume: "https://www.linkedin.com/in/rajatsharma22"
};
```

`devUsername` is used for fetching blog posts from `dev.to`.

---

# Deployment :rocket:

Deploying the app to platforms like Vercel or Netlify is quick and easy.

# FAQ:

1. For those facing the issue of "`next` is not recognized as an internal or external command, operable program or batch file."

Run the following command:

```bash

npm install -g next

```

This installs Next.js globally

then do the usual `npm run dev`
