---
title: Prerequisites
order: 100
lang: en
---

# Prerequisites

In order to start using Scully, you need an existing Angular application with **v8.x.x** or **v9.x.x**.

#### IMPORTANT:

_Scully depends on the application's router module in order to generate the website's pages. Your application must include a RouterModule._

You can create a new Angular 9 application by running the following command:

```bash
npx -p @angular/cli ng new my-scully-app --routing
```

If the above command fails, install the Angular CLI globally with the following command:

```bash
npm install -g @angular/cli
```

Then, create a new application.

```bash
ng new my-scully-app --routing
```

Find more info about the Angular CLI here [👉 angular.io/cli](https://angular.io/cli)

#### IMPORTANT:

_Scully uses Chromium. Therefore, your Operating System, as well as its administrator rights must allow its installation and execution._

### Node version:

- Node.js 10 or higher.
