# Next.js + TypeScript + Tailwind CSS Docker Boilerplate

This is an open-source boilerplate to bootstrap your Next.js projects with Docker, TypeScript, and Tailwind CSS. It is designed to speed up your development process, providing a ready-to-go template that incorporates best practices for these technologies.

## Features

- [Next.js](https://nextjs.org/) 13.4 for building highly scalable, server-rendered React applications.
- [TypeScript](https://www.typescriptlang.org/) for static typing in JavaScript, improving readability and maintainability.
- [Tailwind CSS](https://tailwindcss.com/) for utility-first CSS, which is highly customizable and perfect for component-based frameworks like React.
- [Docker](https://www.docker.com/) for containerizing your applications, ensuring that they run consistently across any platform.

Additionally, this boilerplate contains a second Docker container with a production build of your application running on port 3001. This allows you to verify the build process and preview the production version of your application as you develop it.

## Prerequisites

Before you begin, ensure you have installed:

- [Docker](https://www.docker.com/products/docker-desktop) and Docker Compose

## Installation

```bash
# Clone this repository
git clone https://github.com/pavelee/docker-next13.git

# Navigate into the directory
cd docker-next13

# Run the application
docker-compose up -d
```

Your application should now be running on http://localhost:3000.

Additionally, a production version of your application should be running on http://localhost:3001. You can use this to check how your application will look and function in a production environment.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

MIT
