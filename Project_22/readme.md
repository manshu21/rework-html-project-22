** AI Project Landing Page **

A clean and modern AI-themed landing page built using **HTML5** and **Tailwind CSS**. This project was created as a frontend practice project to recreate a professional SaaS-style hero section with a modern user interface, call-to-action buttons, floating dashboard cards, and an attractive gradient background.

The landing page is designed to showcase how AI and productivity-focused products present information in a visually engaging and user-friendly manner.

** Features **

1. Modern and responsive navigation bar
2. AI-focused hero section
3. Call-to-action buttons
4. Floating dashboard cards
5. Task tracking widget
6. Project status widget
7. Team activity widget
8. Beautiful gradient background
9. Font Awesome icons integration
10. Clean and minimal UI design
11. Built with Tailwind CSS utility classes

** Technologies Used **

1.HTML5
2.Tailwind CSS
3.Font Awesome

** Navigation Bar **

The navigation bar includes:

1. Brand logo
2. Product link
3. Solutions link
4. Resources link
5. Pricing link
6. Login option
7. Primary CTA button

** How to Run the Project **

1. Clone the Repository
2. Navigate to the Project Folder
3. Open the Project
4. open the `index.html` file in your browser.

<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Hero Landing Page</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
    />
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  </head>
  <body class="font-sans m-0 p-0 overflow-y-hidden">
    <header>
      <div class="flex mt-5 mx-20 py-2">
        <img
          class="w-auto h-6 cursor-pointer"
          src="resources/img/logo.png"
          alt=""
        />
        <p class="font-bold cursor-pointer">Project</p>
        <div class="grid grid-cols-5 ml-auto gap-4">
          <a class="px-2" href="#">Product</a>
          <a class="px-2" href="#">Solutions</a>
          <a class="px-2" href="#">Resources</a>
          <a class="px-2" href="#">Pricing</a>
          <a class="px-2 font-bold" href="#">Log in</a>
        </div>
        <div class="mr-4 -mt-3">
          <button class="bg-black w-30 p-3 rounded text-white cursor-pointer">
            Get AI free
          </button>
        </div>
      </div>
    </header>
    <section
      class="bg-gradient-to-r from-[#ffe7d0f9] to-white min-h-screen relative"
    >
      <div class="flex place-content-center">
        <h1 class="font-bold text-3xl mt-2">
          <span class="pl-4">Write, plan, share.</span> <br />With AI at your
          side.
        </h1>
      </div>
      <div>
        <p class="flex place-content-center mt-4">
          It is the connected workspace where better,faster work happens.Now
          with AI.
        </p>
      </div>
      <div class="flex place-content-center mt-8 gap-2">
        <button class="bg-black p-3 rounded text-white cursor-pointer">
          Get AI free <i class="fa-solid fa-arrow-right"></i>
        </button>
        <button class="bg-blue-600 p-3 rounded text-white cursor-pointer">
          Request a demo
        </button>
      </div>

      <div class="flex w-50 h-20 bg-white shadow-md absolute top-1/2 left-30">
        <i
          class="flex place-content-center h-10 w-10 fa-solid fa-book card-icon text-pink-400 bg-pink-200 rounded mx-2 my-2 pl-2"
        ></i
        ><span class="font-bold mt-4">Tasks</span>
        <p class="mt-13 -ml-23">12 tasks completed today.</p>
      </div>

      <div class="flex place-content-center">
        <img
          class="items-center h-60 w-auto mt-10"
          src="resources/img/hero-img.avif"
          alt="hero-image"
        />
      </div>

      <div
        class="flex w-50 h-20 bg-white shadow-md absolute bottom-80 right-50"
      >
        <i
          class="fa-solid fa-check project-icon flex place-content-center mt-2 ml-2 pl-1 text-green-400 bg-green-200 rounded h-10 w-8"
        ></i>
        <p class="font-bold mt-3 ml-2">
          Project status <br />
          <span class="flex place-content-start text-green-400 -ml-5 mt-2"
            >On Track</span
          >
        </p>
      </div>

      <div
        class="flex w-50 h-20 bg-white shadow-md absolute bottom-30 right-70"
      >
        <p class="font-bold ml-4 mt-2">
          Team Activity
          <img
            class="h-8 w-20 ml-2 mt-1 rounded"
            src="resources/img/users.png"
            alt="users"
          />
        </p>
        <span class="mt-9"> +5 online</span>
      </div>
      <div class="bg-black text-white h-10 w-10 fixed bottom-6 right-6 z-50">
        <i class="fa-solid fa-comment text-lg ml-2 mt-2"></i>
      </div>
    </section>

  </body>
</html>
