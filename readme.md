# Build and Deploy an Awwwards Winning Website | React.js, Tailwind CSS, GSAP

https://www.youtube.com/watch?v=zA9r5zTllx4

## Terminal Steps

### Step 1

```zsh
npm create vite@latest ./
name: animated-react
React
JavaScript
npm install

npm run dev

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

http://localhost:5173/

### Step 2 - Configure: tailwind.config.js

```js
 content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  ```

  ### Step 3 - Create: ./src/index.css

  ```js
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Step 4 - 

- Import public folder from: https://github.com/adrianhajdin/award-winning-website/tree/main/public

### Step 5 - Install React Icons

```zsh
npm install react-icons --save
```

### Step 5 - Install GSAP

```zsh
npm install @gsap/react gsap
```