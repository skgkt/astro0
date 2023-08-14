# Started

Run `create astro` command.

```sh
pnpm create astro@latest
```

Installing Astro.

```plaintext
 astro   v2.10.7 Launch sequence initiated.

   dir   Where should we create your new project?
         .

  tmpl   How would you like to start your new project?
         Include sample files
      ✔  Template copied

  deps   Install dependencies?
         Yes
      ✔  Dependencies installed

    ts   Do you plan to write TypeScript?
         Yes

   use   How strict should TypeScript be?
         Strict
      ✔  TypeScript customized

   git   Initialize a new git repository?
         Yes
      ✔  Git initialized

  next   Liftoff confirmed. Explore your project!

         Enter your project directory using cd ./astro0
         Run pnpm dev to start the dev server. CTRL+C to stop.
         Add frameworks like react or tailwind using astro add.

         Stuck? Join us at https://astro.build/chat
```

Created `package.json` file.

```json
{
  "name": "astro0",
  "type": "module",
  "version": "0.0.1",
  "scripts": {
    "dev": "astro dev",
    "start": "astro dev",
    "build": "astro build",
    "preview": "astro preview",
    "astro": "astro"
  },
  "dependencies": {
    "astro": "^2.10.7"
  }
}
```

Start Astro.

```sh
pnpm run dev
```

```plaintext

> astro0@0.0.1 dev C:\Users\keont\code\astro0
> astro dev

   astro  v2.10.7 started in 470ms

  ┃ Local    http://localhost:3000/
  ┃ Network  use --host to expose
```
