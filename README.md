# tailwind
tailwind css integration
Extensions to be used for development

1. ****Tailwind CSS IntelliSense****
2. Live server

Steps to install tailwind.

1. npm init (if package.json file not exists)
2. npm install -D tailwindcss postcss autoprefixer
3. npm install vite
4. npx tailwindcss init (to genereate tailwind.config.js)


tailwind.config.js should be look as below.

module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}


Commands to be run for the project.
1. npm run start (to run the project)
2. npm run tw:build (to build tailwind css)
