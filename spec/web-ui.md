# Documentation for frontend

> Docs description here.

## Table of Contents

- [Documentation for frontend](#documentation-for-frontend)
  - [Table of Contents](#table-of-contents)
  - [📦 Spesification(#-repositories-)](#-spesification-repositories-)
  - [⚙️ Spesification(#-spesification-)](#️-spesification-spesification-)
    - [Frontpages](#frontpages)
    - [Backoffice](#backoffice)
  - [🧱 Tech Stack 🔝](#-tech-stack-)
    - [Core](#core)
    - [Styling](#styling)
    - [Utils](#utils)
  - [🏛️ Application Structure 🔝](#️-application-structure-)
  - [🏁 Getting Started 🔝](#-getting-started-)
  - [👤 Authors 🔝](#-authors-)
  - [🤝 Contribution 🔝](#-contribution-)
  - [📝 License 🔝](#-license-)

## 📦 Spesification(#-repositories-)

Related repositories:
- [`main`](hhttps://github.com/adeka-factory/poneglyph): Main documentation and design
- [`frontend-ui`](https://github.com/adeka-factory/poneglyph/spec/../../../../../web-ui.md): Frontend application
- [`backend-api`](https://github.com/adeka-factory/poneglyph/spec/../../../web-api.md): Backend application

## ⚙️ Spesification(#-spesification-)

Enviroment have a two options : 
 - `development` pages in progress
 - `done` pages already done

### Frontpages

| Path           | Pages / Component | Description         | Environment   |
| -------------- | ----------------- | ------------------- | ------------- |
| `/`            | `PageHome`        | Home                | -             |
| `/about`       | `PageAbout`       | About               | -             |
| `/users`       | `PageUsers`       | All users           | -             |
| `/:slug`       | `PageUserProfile` | Single user profile | -             |
| `/items`       | `PageItems`       | All items           | -             |
| `/items/:slug` | `PageItem`        | Single item detail  | -             |
| `/register`    | `PageRegister`    | Register new user   | -             |
| `/login`       | `PageLogin`       | Login user          | -             |
| `/logout`      | `PageLogout`      | Logout user         | -             |
| `/settings`    | `PageSettings`    | User settings       | `done`             |
| `/404`         | `PageNotFound`    | Not found           | `development` |
| `/upload`      | `PageUpload`      | Upload mode         | `development` |
| `/debug`       | `PageDebug`       | Debug mode          | `development` |

### Backoffice

| Path                      | Pages / Component | Description       | Environment |
| ------------------------- | ------------------| ----------------- | ----------- |
| `/`                       | `PageHome`        | Home              | -           |
| `/404`                    | `PageNotFound`    | Not found         | -           |
| `admin/users`             | `PageUsers`       | All users         | -           |
| `admin/users/:username`   | `PageUser`        | Single user info  | -           |
| `admin/items`             | `PageItems`       | All items         | -           |
| `admin/items/:slug`       | `PageItem`        | Single item info  | -           |
| `admin/images`            | `PageImages`      | All images        | -           |
| `admin/images/:slug`      | `PageImage`       | Single image info | -           |
| `admin/login`             | `PageLogin`       | Login user        | -           |
| `admin/logout`            | `PageLogout`      | Logout user       | -           |


## 🧱 Tech Stack [🔝](#table-of-contents)

All the frontend/web dependencies sorted by priority:

### Core

- [**Git**]() — Distributed version control system
  - [**GitHub**]() — Provides hosting for software development and version control using Git.
- [**JavaScript**]() — The primary programming language
  - [**Node.js**]() — JavaScript runtime environment and package manager.
  - [**Yarn**]() — JavaScript runtime environment and package manager.
- [**REST API**]() — REpresentational State Transfer, architectural style for distributed hypermedia systems.
- [**React**]() — JavaScript library for building user interfaces
  - [**Webpack**]() — JavaScript module bundler.

### Styling

- [**CSS IN JS**]() — For make reusable styling in react components.
  - [**Emotion**]() — Provides hosting for software development
  - [**Styled components**]() — Provides hosting for software development.
  - [**react-responsive**]() — Provides hosting for software development.

### Utils
- [**Prettier**]() — For make reusable styling in react components.
- [**Husky**]() — For make reusable styling in react components.
- [**webpack-analyze**]() — For make reusable styling in react components.

## 🏛️ Application Structure [🔝](#table-of-contents)

WIP

## 🏁 Getting Started [🔝](#table-of-contents)

WIP

## 👤 Authors [🔝](#table-of-contents)

WIP

## 🤝 Contribution [🔝](#table-of-contents)

WIP

## 📝 License [🔝](#table-of-contents)