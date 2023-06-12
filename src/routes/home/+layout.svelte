<!--- add header -->
<div class="container flex">
    <div class="logo flex-none pr-20">
        <img src="https://www.marksalvana.com/images/logo.png" alt="Mark Salvana" />
    </div>
    <div class="header flex-auto">
        <header>
            <h1 class="text-3xl underline bg-green">Header</h1>
            <nav>
                <ul class="flex flex-row">
                    <li class="px-10"><a href="/">Home</a></li>
                    <li class="px-10"><a href="/about">About Us</a></li>
                    <li class="px-10"><a href="/contact">Contact Us</a></li>
                </ul>
            </nav>
        </header>

    </div>
    <div class="flex-auto">3rd column</div>

</div>

<div class="flex">
    <div class="flex-auto">
      01
    </div>
    <div class="flex-auto w-64">
      02
    </div>
    <div class="flex-auto w-32">
      03
    </div>
  </div>

<!--- add slot -->
<slot />

<h1>this is a test</h1>