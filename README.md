# File handling with s3

This example project serves as an exploration of Amazon Simple Storage Service (S3) capabilities, showcasing an implementation of some key features for developers. The project focuses on various aspects, including upload and download functionalities using signed URLs, bucket versioning, archiving, retrieval, and multipart uploads.

The project uses [SST](https://sst.dev) for deploying AWS Resources and [Turso](https://turso.tech) for storing data in a SQLite Database.
UI is built with [SvelteKit](https://kit.svelte.dev/) but can be easily replaced with a technology of your choosing. [React Form](https://react.email/) is used for
composing a HTML Email.

## Getting Started

- Configure AWS credentials using the AWS CLI
- Install dependencies with `npm install` (assuming Node.js is installed).
- Deploy infrastructure to aws with `npx sst dev`
- Launch app with `npm run dev`

Feel free to use and extend this project as a foundation for integrating AWS S3 features into your applications. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. Happy coding!
