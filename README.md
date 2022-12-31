# GitHub Repo for the Hero Section tutorial video

You can also totally build this with regular CSS, though it might take you longer.

## Links
- [YouTube Video](https://youtu.be/4wGgkZ7rY9k)
- Tailwind CDN: `<script src="https://cdn.tailwindcss.com/"></script>`


## Template Code
```html
<!-- Hero Section -->
<section class="flex flex-col min-h-screen bg-slate-800 text-white bg-center bg-cover bg-blend-overlay bg-fixed bg-black/30" style="background-image: url('https://source.unsplash.com/random/')">

    <!-- Navbar -->
    <div class="flex items-center h-20">
        <!-- Navbar Container -->
        <div class="mx-auto relative px-5 max-w-screen-xl w-full flex items-center justify-end">
        <!-- Navbar Logo -->
        <div class="text-4xl font-light uppercase absolute left-1/2 top-1/2 -translate-y-1/2 -translate-x-1/2">
            My Site
        </div>

        <!-- Navbar Menu -->
        <nav class="flex gap-5">
            <a>Home</a>
            <a>Login</a>
            <a>Signup</a>
        </nav>
        </div>
    </div>

<!-- Hero Section Content -->
<div class="flex-1 flex items-center">
    <div class="text-center mx-auto">
    <h1 class="text-6xl font-semibold">Welcome to my site!</h1>
    <p class="font-light text-3xl mt-5">The land of opportunity.</p>
    <a class="px-5 py-2 inline-block bg-cyan-500 text-white hover:bg-cyan-400 transition-colors mt-10" href="">
        Get Started
    </a>
    </div>
</div>
</section>
```