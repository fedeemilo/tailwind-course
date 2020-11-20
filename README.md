# Tailwind CSS 2.0

### Installation
```
  npm install tailwindcss postcss autoprefixer
```

### Create tailwind config file
```
  npx tailwindcss init
```
### Inject Tailwind's base, components, and utilities styles:
```css
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```

### Command to build tailwind style.css file
```
  npx tailwindcss build ./css/style.css -o ./css/dist.css
```
