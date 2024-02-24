<script>
  import { openModal } from "../store";
</script>

<header class="flex flex-col relative z-20">
  <div
    class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6"
  >
    <a
      class="duration-200 text-xl hover:text-indigo-400 curson-pointer"
      href="/"
    >
      <h1 class="font-semibold">
        Gym <span class="text-indigo-400">Bricks</span>
      </h1>
    </a>
    <button
      on:click={() => ($openModal = true)}
      class="md:hidden grid place-items-center"
    >
      <i class="fa-solid fa-bars"></i>
      <nav class="hidden md:flex items-center gap-4 lg:gap-6">
        <a
          class="duration-200 hover:text-indigo-400 curson-pointer"
          href="#product">Product</a
        >
        <a
          class="duration-200 hover:text-indigo-400 curson-pointer"
          href="#reviews">Reviews</a
        >
        <a class="duration-200 hover:text-indigo-400 curson-pointer" href="#faq"
          >FAQ'S
        </a>
        <button class="specialBtn">Start Free Today</button>
      </nav>
    </button>
  </div>
</header>
