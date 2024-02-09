# Gym Website

## Technologies Used:
- Vite
- React
- TypeScript
- FramerMotion
- Tailwind CSS

---

### Steps for Getting Started:

Starting the Project Installation with Vite:

```
npm create vite@latest
```

Give the name of the Project of your choice.
Select React as the Framework in the Menu.
Select TypeScript as the language of Choice.

Change the Directory of Command Line Tool to the named Project.

Then install the required Node packages by using the command:

```
npm install
```

Then install the additional libraries like Framer Motion, React Anchor Link Smooth Scroll, Heroicons for React by using the following command:

```
npm i framer-motion react-anchor-link-smooth-scroll@1.0.12 @heroicons/react
```

Install additional Dev Dependencies using following command:

```
npm i -D @types/react-anchor-link-smooth-scroll@1.0.2 @types/node
```

Replace the Assets folder locally with the one in the repository for the images.

Delete the App.css and delete the import from App.tsx as well.

Clean up the App.tsx by deleting everything and just keeping the function with a single div with classname "app".
Delete everything from index.css.

Update the vite.config.ts, tsconfig.json files according to that of the repository.

Tailwind CSS installation using Vite:

Use the following commands for installation:

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Replace the content of tailwind.config.js with that of from the repository file.

Replace the content of index.css with that of the file from repository.

Install the Tailwind Prettier Plugin using the following command:

```
npm i -D prettier prettier-plugin-tailwindcss
```

Create a "prettier.config.cjs" file at the root and replace the content with that of the repository file.

This are all the necessary steps for the Setup of the Project.

---