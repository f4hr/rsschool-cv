# Ilya Fakhrutdinov

## Contacts

- **Email:** [ilyaf4hr@gmail.com](mailto:ilyaf4hr@gmail.com)
- **Telegram:** [@ilyaf4hr](https://t.me/ilyaf4hr)
- **Location:** Ufa, Russia

## About me

> Frontend Developer with 2 years of work experience as Web Developer in small local studio.

I enjoy making web applications. Always learning new things but not forgetting about fundamentals. \
Currently my main focus is on `JavaScript` and Frontend development in general. \
I am also learning about Backend development and `Ruby` and `Ruby on Rails` to get more thorough understanding about how the Web works and get a taste of a different language.

## Skills

- JavaScript / TypeScript
- React
- CSS / SCSS / PostCSS / BEM
- Git / GitHub
- Docker
- Figma / Photoshop

## Code Examples

### Does my number look big in this?

> A Narcissistic Number (or Armstrong Number) is a positive number which is the sum of its own digits, each raised to the power of the number of digits in a given base.

Codewars Kata: https://www.codewars.com/kata/5287e858c6b5a9678200083c

```ts
export function narcissistic(value: number): boolean {
  const digits = String(value).split('').map(Number);
  return value === digits.reduce((sum, d) => sum + d ** digits.length, 0);
}
```

## Personal Projects

### Kanban

SPA for working with kanban boards (similar to Trello) \
GitHub: [https://github.com/f4hr/kanban](https://github.com/f4hr/kanban)

- **Frontend:** TypeScript, React, Tanstack Query (React Query), Wouter, React Hook Form, React Beautiful DND.
- **Backend:** TypeScript, Fastify, OpenAPI, MongoDB, Mikro-ORM
- **CI/CD:** GitHub + Dokku

### Chat

Real-time application built with React/Redux and websocket \
GitHub: [https://github.com/f4hr/frontend-project-lvl4](https://github.com/f4hr/frontend-project-lvl4)

- **Frontend:** JavaScript, React (Hooks), Redux (@reduxjs/toolkit), Formik, socket.io, REST API
- **Backend:** JavaScript, Fastify
- **CI/CD:** GitHub + Dokku

## Work Experience

- **2018/10 - 2021/05** Web Developer at *Spacelab*, Ufa
    - Created 20+ websites (landing pages, corporate, ecommerce)
    - Integrated websites with 3rd party API's (amoCRM, YooMoney)
    - Done some basic DevOps (DNS, domains, hosting management)
    - Built Telegram Bot with Trello integration for company's internal usage
