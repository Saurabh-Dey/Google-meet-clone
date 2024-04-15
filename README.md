# Google Meet Clone (Visual Sync)

## Introduction

- Built with the latest Next.js and TypeScript, this project replicates Zoom, a widely used video conferencing tool. It enables users to securely log in, create meetings and access various meeting functionalities such as recording, screen sharing, and managing participants.

## Tech Stack
* Next.js
* TypeScript
* Clerk
* getstream
* shadcn
* Tailwind CSS

## Features
- Authentication: Implements authentication and authorization features using Clerk, allowing users to securely log in via social sign-on or traditional email and password methods, while ensuring appropriate access levels and permissions within the platform.

-  New Meeting: Quickly start a new meeting, configuring camera and microphone settings before joining.
- Meeting Controls: Participants have full control over meeting aspects, including recording, emoji reactions, screen sharing, muting/unmuting, sound adjustments, grid layout, participant list view, and individual participant management (pinning, muting, unmuting, blocking, allowing video share).
- Exit Meeting: Participants can leave a meeting, or creators can end it for all attendees.
-  Schedule Future Meetings: Input meeting details (date, time) to schedule future meetings, accessible on the 'Upcoming Meetings' page for sharing the link or immediate start.
-  Past Meetings List: Access a list of previously held meetings, including details and metadata.
-  View Recorded Meetings: Access recordings of past meetings for review or reference.
-  Personal Room: Users have a personal room with a unique meeting link for instant meetings, shareable with others.
-  Join Meetings via Link: Easily join meetings created by others by providing a link.
-  Secure Real-time Functionality: All interactions within the platform are secure and occur in real-time, maintaining user privacy and data integrity.
-  Responsive Design: Follows responsive design principles to ensure optimal user experience across devices, adapting seamlessly to different screen sizes and resolutions.

and many more, including code architecture and reusability.


## Quick Start:
Follow these steps to set up the project locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
* Git
* NodeJS
* npm

1. Clone the repository:
   ```sh
   git clone https://github.com/Saurabh-Dey/Google-meet-clone.git
2. Navigate to the Repository Directory Change into the directory that was created by the clone command:
   ```sh
   cd your-repository-directory
3. Install Dependencies Run the following command to install all the dependencies listed in the package.json file:
   ```sh
   npm install


### Set Up Environment Variables

Create a new file named `.env` in the root of your project and add the following content:

```sh
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

   NEXT_PUBLIC_STREAM_API_KEY=
   STREAM_SECRET_KEY=
   NEXT_PUBLIC_BASE_URL=localhost:3000
```

Replace the placeholder values with your actual Clerk & getstream credentials. You can obtain these credentials by signing up on the <a href="https://clerk.com/">Clerk </a> website and <a href="https://getstream.io/">getstream </a> website


### Running the Project
   ```sh
   npm run dev
  ```



# Hi there, I'm Sourav Dey 👋

## Intern MERN Stack Developer

I'm passionate about building and contributing to the web ecosystem with the MERN stack. Here's a bit about me:

- 🔭 I’m currently working on web applications using **MongoDB**, **Express.js**, **React**, and **Node.js**.
- 🌱 I’m currently learning about **TypeScript** and **WebRTC**.
- 👯 I’m looking to collaborate on **open-source projects** and **innovative web solutions**.
- 💬 Ask me about anything related to **JavaScript**, **React**, and **building REST APIs**.
- ⚡ Fun fact: I love to explore new technologies and contribute to developer communities!
