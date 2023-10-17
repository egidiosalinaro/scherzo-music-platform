<a name="readme-top"></a>

  <h1 align="center">Scherzo :musical_note: Music, for real</h1>

  <p align="center">
  An open-source full stack application for music streaming and sharing. <br> [Try it Here!](https://scherzo-music-platform.vercel.app/)
  </p>

<!-- TABLE OF CONTENTS -->

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#question-about-the-project">About The Project</a>
      <ul>
        <li><a href="#joystick-usage">Usage</a></li>
        <li>
          <a href="#bricks-built-with">Built With</a>
          <ul>
          <li><a href="#-back-end">Back End</a></li>
          <li><a href="#-front-end">Front End</a></li>
          </ul>
        </li>
      </ul>
    </li>
    <li>
      <a href="#clapper-getting-started">Getting Started</a>
      <ul>
        <li><a href="#pencil-prerequisites">Prerequisites</a></li>
        <li><a href="#gear-installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#world_map-roadmap">Roadmap</a></li>
    <li><a href="#computer-contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## :question: About The Project

Scherzo is the new open-source streaming service that lets you upload your music, listen to any song uploaded, like your favorite songs. You can use it with a free plan or the premium one.

### :joystick: Usage

You can sign up / sign in using email and other methods (more coming soon). Some features are for premium users only (_during this test period, you can use a fake 4242424242424242 card to subscribe_).

- _<ins>Your Library</ins>_: a list of songs uploaded by you. Add more using the **+** button

- _<ins>New Music</ins>_: latest songs uploaded by all users

- _<ins>Player</ins>_: use it to listen to songs

- _<ins>Search</ins>_: search any song

- _<ins>Favorites</ins>_: you can find here all song you liked using the ♡ button

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### :bricks: Built With

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

#### 🖥 Back End

<div style="display:flex;  align-items:center;"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" width="40" height="40" style="border-radius:100%; margin-right:9px;"/> </a>PostgreSQL</div> <br>
<div style="display:flex;  align-items:center;"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://github.com/egidiosalinaro/spotify-clone/assets/129901135/5cf0ceb6-b549-4963-a705-f6e4fa3b536a" alt="Supabase" width="40" height="40" style="border-radius:100%; margin-right:9px;"/> </a>Supabase</div> <br>
<div style="display:flex;  align-items:center;"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://github.com/egidiosalinaro/spotify-clone/assets/129901135/8cd837f0-497f-4896-b2fb-81ad08821a93" alt="Stripe" width="40" height="40" style="border-radius:100%; margin-right:9px;"/> </a>Stripe</div>

#### 👩‍💻 Front End

<div style="display:flex;  align-items:center;"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next JS" width="40" height="40" style="border-radius:100%; margin-right:9px;"/> </a>Next JS</div> <br>
<div style="display:flex;  align-items:center;"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" width="40" height="40" style="border-radius:100%; margin-right:9px;"/> </a>React</div> <br>
<div style="display:flex;  align-items:center;"><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" alt="Tailwind CSS" width="40" height="40" style="border-radius:100%; margin-right:9px;"/> </a>Tailwind CSS</div> <br>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## :clapper: Getting Started

I deployed my Next.js app using the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js. <br>
Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

You can also start this app on your local machine, following these steps:

### :pencil: Prerequisites

- clone this repository

  ```sh
  git clone https://github.com/egidiosalinaro/scherzo-music-platform
  ```

- install all libraries and dependencies needed for this app

  ```sh
  npm install
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### :gear: Installation

Once downloaded this repo, you are ready to go. <br> Now you can:

- configure your Supabase database as I did

  to match the routes called in this repo, your Supabase database should have two buckets called `songs` and `images`, and seven tables called `customers`, `liked_songs`, `prices`, `products`, `songs`, `subscriptions`, `users`

- connect your Supabase and Stripe account

  create a `.env.local` file (you won't find mine because it is in the `.gitignore` list) containing all the environment variables required for Supabase and Stripe to work, and fill them with your own keys

  ```sh
  NEXT_PUBLIC_SUPABASE_URL=
  NEXT_PUBLIC_SUPABASE_ANON_KEY=
  SUPABASE_SERVICE_ROLE_KEY=

  NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
  STRIPE_SECRET_KEY=
  STRIPE_WEBHOOK_SECRET=
  ```

- start the app locally

  ```sh
  npm run dev
  ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see Scherzo in action.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## :world_map: Roadmap

- [x] `.env.local` file containing keys
- [x] setting up Supabase
- [x] app and pages configuration
- [x] creating components with Tailwind classes
- [x] creating hooks and actions
- [x] creating providers
- [x] setting up Stripe

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## :computer: Contributing

I welcome contributions from the open-source community. If you'd like to help improve ToolBox, please follow our contribution guidelines:

- Report any bugs or issues you encounter by creating a GitHub issue.

- Suggest new features and improvements by submitting a feature request.

- Contribute code by forking the repository and opening a pull request.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

egidiosalinaro@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>
