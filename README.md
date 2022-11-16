# Theme

An uber performant 11ty theme. We use it for the GV docs and the GV blog.

Based on google's [eleventy-high-performance-blog](https://github.com/google/eleventy-high-performance-blog).

## Getting Started

### 1. Generate a new repository from this repository template

Click the ["Use this template"](https://github.com/google/eleventy-high-performance-blog/generate) button. Alternatively you can clone this repo yourself and push your copy to your favorite git repository.

### 2. Clone your new repository

```
git clone https://github.com/YOUR_REPO
```

### 3. Navigate to the directory

```
cd my-blog-name
```

### 4. Install dependencies

```
npm install
```

### 5. Build, serve, watch and test

```
npm run watch
```

### 6. Build and test

```
npm run build
```

## Customize

-   Search for "Update me" across files in your editor to find all the site specific things you should update.
-   Update the favicons in 'img/favicon/'.
-   Otherwise: Knock yourself out. This is a template repository.
-   For a simple color override, adjust these CSS variables at the top of `css/main.css`.

```css
:root {
    --primary: #e7bf60;
    --primary-dark: #f9c412;
}
```
