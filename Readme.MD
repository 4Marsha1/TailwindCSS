# Tailwind CSS

https://tailwindcss.com/docs/

## Steps

### 1. Install tailwind css

```
npm i tailwindcss
npx tailwindcss init
```

### 2. Add content to tailwind.config.js

```
content: ["./src/**/*.{html,js}",'./public/index.html'],
```

### 3. Make /src/styles.css and add

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 4. Add new script

```
"build-css": "tailwindcss -i ./src/styles.css -o ./public/styles.css"
```

### 5. Use /public/styles.css in HTML files

```
<link rel="stylesheet" href="./styles.css">
```
