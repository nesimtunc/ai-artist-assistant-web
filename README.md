# AI Artist Assistant Web

AI Artist Assistant Web is an open-source project aimed at building a community-driven platform for generating lyrics, songs, and potentially enabling chat functionality with famous artists and individuals who have passed away. The project is designed to be generic and adaptable, allowing it to be used with any artist or person for whom there is sufficient data.

This repository contains the frontend and backend code for the community-driven platform, where users can submit content, vote on submissions, flag content, and donate. It includes the web interface built with Node.js, Express, TypeScript, and PostgreSQL, as well as the API for interacting with the AI models in the [ai-artist-assistant repository](https://github.com/nesimtunc/ai-artist-assistant).

Current Artist: [Ahmet Kaya](https://en.wikipedia.org/wiki/Ahmet_Kaya)

## Features

- User-friendly interface: A modern and responsive web interface for users to interact with the platform.
- Content submission and voting: Users can submit content, vote on submissions, and flag inappropriate content.
Donations and Transparency: A transparent crowdfunding system to help support server costs, AI training resources, and community involvement, as well as to support selected charitable causes.
- API integration: The backend API communicates with the AI models in the `ai-artist-assistant` repository to generate content based on user submissions.

## Getting Started

To set up the project on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/ai-artist-assistant-web.git`
2. Change the current directory to the project directory: `cd ai-artist-assistant-web`
3. Install the required dependencies: `npm install`
4. Set up your environment variables, such as API keys or other configurations, in a `.env` file or as system environment variables.
5. Run the development server: `npm run dev`
6. Open your browser and navigate to `http://localhost:3000` to view the web application.

## Contributing

We welcome contributions from the community! Whether you're interested in adding new features, fixing bugs, or improving documentation, your input is valuable to the project's growth. To contribute, follow these steps:

1. Fork the repository to your own GitHub account.
2. Clone the forked repository to your local machine: `git clone https://github.com/yourusername/ai-artist-assistant-web.git`
3. Create a new branch for your feature or bugfix: `git checkout -b your-feature-branch`
4. Make your changes and commit them with a descriptive commit message.
5. Push your changes to your forked repository: `git push origin your-feature-branch`
6. Create a pull request in the original `ai-artist-assistant-web` repository, describing your changes and their purpose.

We will review your pull request and provide feedback or merge the changes if they align with the project's goals.

## License

This project is licensed under the [Creative Commons License](LICENSE). See the LICENSE file for more information.

## Acknowledgements

We would like to express our gratitude to the community for their support and contributions to this project. Your passion for preserving the legacy of great artists and individuals inspires us to continuously improve and expand the capabilities of AI Artist Assistant.
