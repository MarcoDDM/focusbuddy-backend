<a name="readme-top"></a>

<div align="center">

  <img src="soyMarco.png" alt="logo" width="140"  height="auto" />
  <br/>

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Author](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 FocusBuddy <a name="about-project"></a>

**FocusBuddy** is an application specifically designed to assist individuals diagnosed with ADHD (Attention Deficit Hyperactivity Disorder) manage their daily tasks and enhancing their focus. Living with ADHD can present challenges in organizing tasks and maintaining concentration over time. FocusBuddy aims to alleviate these challenges by providing structured task management capabilities and features that promote sustained attention.

By leveraging its user-friendly interface and intuitive task management system, FocusBuddy enables users to:

- **Create and Organize Tasks**: Easily create, edit, and categorize tasks based on priority and deadlines.
- **Track Progress**: Monitor task completion and review task history to evaluate productivity over time.
- **Receive Reminders**: Set reminders for important tasks to help maintain focus and reduce forgetfulness.
- **Enhance Focus**: Utilize features to minimize distractions and optimize workflow efficiency.

FocusBuddy integrates seamlessly into daily routines, offering a supportive toolset tailored to the unique needs of individuals with ADHD. Whether at work, school, or home, FocusBuddy strives to empower users to achieve greater productivity and success in their daily lives.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://nodejs.org/">Node.js</a></li>
    <li><a href="https://expressjs.com/">Express.js</a></li>
    <li><a href="https://www.mongodb.com/">MongoDB</a></li>
    <li><a href="https://mongoosejs.com/">Mongoose</a></li>
  </ul>
</details>

<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://reactjs.org/">React</a></li>
  </ul>
</details>

<details>
  <summary>Authentication</summary>
  <ul>
    <li><a href="https://jwt.io/">JSON Web Tokens (JWT)</a></li>
  </ul>
</details>

<details>
  <summary>Styling</summary>
  <ul>
    <li>CSS</li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

- **Task Management**: Create, edit, and delete tasks.
- **Progress Tracking**: Mark tasks as completed and view task history.
- **Notifications**: Reminders for pending tasks.
- **Security**: Secure authentication and authorization using JWT.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->

## 🚀 Live Demo <a name="live-demo"></a>

- **Non deployed yet.**

<!--  [Live Demo Link](https://example.com)-->

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites <a name="prerequisites"></a>

Before running this project you need:

- Node.js and npm
- MongoDB

### Setup <a name="setup"></a>

Clone this repository to your desired folder:

```sh
git clone https://github.com/<your-github-username>/focusbuddy-backend.git
cd focusbuddy-backend
```

### Install <a name="install"></a>

Install backend dependencies:

```sh
npm install
```

Create a `.env` file in the root of the project with the following content:

```
MONGO_URI=mongodb://localhost:27017/focusbuddy
JWT_SECRET=your_jwt_secret_key
```

### Usage <a name="usage"></a>

To start the server, run:

```sh
npm start
```

Access the API at `http://localhost:5000`.

### Run tests <a name="run-tests"></a>

To run tests, use:

```sh
npm test
```

### Deployment <a name="deployment"></a>

You can deploy this project using:

```sh
npm run deploy
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHOR -->

## 👥 Author <a name="authors"></a>

👤 **Marco Almada**

- GitHub: [@MarcoDDM](https://github.com/<MarcoDDM>)
- LinkedIn: [Marco Almada](https://www.linkedin.com/in/your-nmarcoalmadaar/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **Add multi-user support**
- [ ] **Implement push notifications**
- [ ] **Integrate task calendar**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project, give it a star on GitHub!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgements <a name="acknowledgements"></a>

- Thanks to my mentors and colleagues for their support and feedback.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FAQ -->

## ❓ FAQ <a name="faq"></a>

- **How can I contribute to the project?**
  - You can contribute by opening new issues or developing new features.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is licensed under the [MIT](./LICENSE) License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
