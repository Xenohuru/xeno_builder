# XENOHURU

XENOHURU is an open infrastructure journal and builder community platform designed for African tourism systems. It functions as a workspace linking a web application with a dedicated backend server, supporting local development, API integration, and automated testing.

## Getting Started

To set up the project locally, install the workspace dependencies by running `pnpm install`. Set up your local configuration by copying `.env.example` to `.env` and adjusting variables like `PORT` or `DATABASE_URL` if needed. Start the development environment using `pnpm dev` for the main web application (accessible at `http://localhost:5173`) and `pnpm dev:api` for the backend API server. To verify the project build and test suite, run `pnpm run typecheck`, `pnpm run test`, and `pnpm run build:web`.

## Deployment & Workflows

The web application is configured for static hosting platforms like Vercel, pointing builds directly to the primary frontend package. Automated integration pipelines handle routine typechecking, unit testing, and production builds on push, while scheduled bots manage dependency maintenance. The backend API is designed to run on a Node-compatible host independently from the static frontend client.

## License

This project is open-source software licensed under the **GNU General Public License v3.0 (GPL-v3)**.

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