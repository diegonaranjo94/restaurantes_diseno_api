# Restaurants_api

Sample Project: REST API for Restaurant Management (API Design)

Description
- This folder contains a reference implementation of a REST API built with NestJS, modeling restaurants and dishes. It is used as part of the MISW4403 - API Design and Construction course.

Requirements
- Node.js 16+ (or the version specified in the monorepo)
- npm (or yarn)

Installation
```bash
# From the root of the 'restaurantes_diseno_api' project
npm install
```

Running the Application
```bash
# Development server
npm run start

# With hot-reload (if configured)
npm run start:dev
```

Testing
```bash
# Run included unit/e2e tests
npm test
npm run test:e2e
```

Main Structure
- `src/` — microproject source code
	- `restaurante/` — entities, DTOs, and business logic for restaurants
	- `plato/` — entity and service for dishes
	- `shared/` — testing utilities and interceptors (e.g., error handling)

Highlights
- Implements typical NestJS patterns: modules, controllers, services, and TypeORM entities.
- Includes utilities for testing and TypeORM configuration for test environments.

Recommended Usage
- Review `src/shared/testing-utils/typeorm-testing-config.ts` to run tests with an in-memory or test database.
- Extend DTOs and services to adapt the API to your requirements (authentication, validation, etc.).

Contributing
- Fork the repository, create a branch with your improvement, and open a PR with a clear description.

License
- See the `LICENSE` file in the project root.

---

You can contact me and get more information through:

<div>
  <p align="center">
  <a href="https://www.linkedin.com/in/diegonaranjo94/" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="imorange" height="30" width="40" />
    </a>
  <a href="https://www.instagram.com/diegonaranjo.94/" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="imorange" height="30" width="40" />
    </a>
  <a href="https://github.com/diegonaranjo94" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="imorange" height="30" width="40" />
    </a>
  </p>
</div>
