# Install Tailwind to the React Project

npm install -D tailwindcss postcss autoprefixer

npx tailwind init -p

module.exports = {
  content: ['./src/**/*.{js,jsx,ts,tsx}'],
  theme: {
    extend: {},
  },
  plugins: [],
}

@tailwind base;
@tailwind components;
@tailwind utilities;