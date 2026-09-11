# XENOHURU

XENOHURU is an open infrastructure journal and builder community platform designed for African tourism systems. It functions as a workspace linking a web application with a dedicated backend server, supporting local development, API integration, and automated testing.

## Getting Started

To set up the project locally, install the workspace dependencies by running `pnpm install`. Set up your local configuration by copying `.env.example` to `.env` and adjusting variables like `PORT` or `DATABASE_URL` if needed. Start the development environment using `pnpm dev` for the main web application (accessible at `http://localhost:5173`) and `pnpm dev:api` for the backend API server. To verify the project build and test suite, run `pnpm run typecheck`, `pnpm run test`, and `pnpm run build:web`.

## Deployment & Workflows

The web application is configured for static hosting platforms like Vercel, pointing builds directly to the primary frontend package. Automated integration pipelines handle routine typechecking, unit testing, and production builds on push, while scheduled bots manage dependency maintenance. The backend API is designed to run on a Node-compatible host independently from the static frontend client.

## License

This program is free software: you can redistribute it and/or modify it under the terms of the **GNU General Public License** as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.html) for more details.

## Credits

Created and maintained by the XENOHURU builder community and contributors.

## Explore More

To learn more about the core technologies used in this project, consult their official documentation:

* **React** – [https://react.dev](https://react.dev)
* **Vite** – [https://vitejs.dev](https://vitejs.dev)
* **Express** – [https://expressjs.com](https://expressjs.com)
* **Drizzle ORM** – [https://orm.drizzle.team](https://orm.drizzle.team)
* **PostgreSQL** – [https://www.postgresql.org/docs](https://www.postgresql.org/docs)
* **Vitest** – [https://vitest.dev](https://vitest.dev)