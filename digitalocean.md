# Meocloud Documentation

<!DOCTYPE html>
<html lang="en" class="scroll-smooth">

<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- Change the description wrt project -->
  <meta name="meocloud" content="what have I done" />

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />

  <!-- stylesheets -->
  <link rel="stylesheet" href="./public/styles/style.css">

  <!-- You can add your own fonts from fonts.google.com -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet" />

  <!-- Default Script tags -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="./public/js/index.js"></script>

  <script>
    tailwind.config = {
      darkMode: "class",
    };
  </script>

  <!-- Replace the title name -->
  <title>Meocloud Documentation</title>
</head>

<body style="font-family: 'Poppins', sans-serif; min-height: 100vh; display: flex; flex-direction: column;"
  class="dark:bg-slate-900 bg-white dark:text-white">
  <!-- Header start here -->
  <header class="w-full p-3 border-b dark:border-b  flex sticky top-0 z-10 dark:bg-slate-900 bg-white dark:text-white ">
    <nav
      class="w-full flex flex-col lg:flex-row md:flex-row sm:flex-row items-start lg:item-center md:item-center sm:item-center lg:justify-between md:justify-between sm:justify-between justify-start dark:text-white">
      <ul>
        <!-- You can change your logo name -->
        <li class="font-mono text-xl">
          <a href="./index.html">
          meocloud
        </a>
        </li>
      </ul>
      <ul id="header-nav" class="mr-6 sm:flex md:flex lg:flex hidden">
        <li class="mr-5 mb-3 mt-5 sm:mb-0 sm:mt-0 md:mb-0 md:mt-0 lg:mb-0 lg:mt-0">
          <a href="./docs.html">Documentation</a>
        </li>
        <li class="mr-5 mb-3 mt-5 sm:mb-0 sm:mt-0 md:mb-0 md:mt-0 lg:mb-0 lg:mt-0">
          <a href="#contributors">Meet my Contributor</a>
        </li>
        <div>
          <ul class="flex">
            <!-- Change the href link to your respective social media accounts-->
            <li class="mr-5 flex dark:hidden">
              <p onclick="darkmode()">
                <img src="./public/svgs/sun.svg" alt="sun Link" />
              </p>
            </li>
            <li class="mr-5 hidden dark:flex">
              <p onclick="lightmode()">
                <img src="./public/svgs/sun-dark.svg" alt="sun Link" />
              </p>
            </li>
            <li class="mr-5 flex dark:hidden">
              <a href="https://wa.me/6285883339867"><img src="./public/svgs/whatsapp1.png" alt="whatsapp" /></a>
            </li>
            <li class="mr-5 hidden dark:flex">
              <a href="https://wa.me/6285883339867"><img src="./public/svgs/whatsapp-dark.png" alt="whatsapp" /></a>
            </li>
            <li class="mr-5 flex dark:hidden">
              <a href="https://web.facebook.com/meocloud"><img src="./public/svgs/facebook1.png" alt="facebook" /></a>
            </li>
            <li class="mr-5 hidden dark:flex">
              <a href="https://web.facebook.com/meocloud"><img src="./public/svgs/facebook-dark.png" alt="facebook" /></a>
            </li>
            <li class="flex dark:hidden">
              <a href="https://t.me/meocloud"><img src="./public/svgs/telegram1.png" alt="Telegram" /></a>
            </li>
            <li class="hidden dark:flex">
              <a href="https://t.me/meocloud"><img src="./public/svgs/telegram-dark.png" alt="Telegram" /></a>
            </li>
          </ul>
        </div>
      </ul>
    </nav>

    <div class="sm:hidden flex" onclick="OnclickOpenMenu()" id="open-menu">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd"
          d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM9 15a1 1 0 011-1h6a1 1 0 110 2h-6a1 1 0 01-1-1z"
          clip-rule="evenodd" />
      </svg>
    </div>
    <div class="hidden" onclick="OnclickCloseMenu()" id="close-menu">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
      </svg>
    </div>
  </header>
  <!-- Header ends here -->

  <div class="flex flex-col md:flex-row lg:flex-row">
    <!-- Side menu starts here -->
    <nav
      class="flex ml-10 mt-7 md:fixed lg:fixed"
      data-spy="affix"
      data-offset-top="300"
      data-offset-bottom="200"
      role="navigation"
    >
      <ul class="nav">
        <li class="font-medium"><a href="#link1">Intro</a></li>
        <li class="font-medium">
          <a href="#link2">Custom Images</a>
        </li>
        <li class="font-medium"><a href="#link3">Recovery Mode</a></li>
      </ul>
    </nav>
    <!-- Side Menu ends here -->

    <div class="pl-5 md:pl-[250px] lg:pl-[250px]">
      <!-- Link1 start -->
      <section id="link1">
        <div class="h-full mt-10">
          <p class="font-normal text-2xl">Using Custom Images</p>
          <p class="leading-0 w-3/4">
            <h3>Using Custom Image</h3>
            <!-- rest of your content -->
          </p>
        </div>
      </section>
    </div>
  </div>
</body>

</html>
