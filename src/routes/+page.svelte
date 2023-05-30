<section>
    <h1 class="text-4xl font-bold">
      <span class="text-orange-500">SvelteKit</span>
      <span class="text-amber-500"> + </span>
      <span class="text-sky-500">Tailwind CSS</span>
      <span class="text-amber-500"> + </span>
      <span class="text-orange-400">Flowbite</span>
      <span class="text-amber-500"> + </span>
      <span class="text-yellow-100">DaisyUI </span>
      <span class="text-amber-500"> Application </span>
    </h1>
  
    <div class="parent">
      <div class="div1">
        <a href="https://kit.svelte.dev"><img
          src="https://raw.githubusercontent.com/sveltejs/branding/master/svelte-logo.svg"
          alt=""
        /></a>
        <a href="https://flowbite-svelte.com"><img
          src="https://flowbite-svelte.com/images/flowbite-svelte-icon-logo.svg"
          alt=""
        /></a>
        <a href="https://tailwindcss.com"><img
          src="https://camo.githubusercontent.com/5734d0669fe22ce04a1cb989a156cd32c379875f6bca56d5210c9432824856d9/68747470733a2f2f7777772e766563746f726c6f676f2e7a6f6e652f6c6f676f732f7461696c77696e646373732f7461696c77696e646373732d69636f6e2e737667"
          alt=""
        /></a>
        <!-- <img
          src="https://as2.ftcdn.net/v2/jpg/03/29/27/69/1000_F_329276955_XDx5H5D9KGlY9ckipnevWMCM3weKOZvl.jpg"
          alt=""
        /> -->
      </div>
    </div>
  </section>
  
  <style lang="postcss">
    :global(html) {
      background-color: #352d2c;
    }
    section {
      display: flex;
      align-items: center;
      flex-direction: column;
      margin-top: 30px;
    }
    img {
      width: 100px;
      margin: 50px;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    img:nth-child(1) {
      filter: drop-shadow(4px 4px 10px rgba(0, 0, 0, 0.25));
    }
    img:nth-child(3) {
      filter: drop-shadow(6px 6px 10px rgba(3, 71, 143, 0.708));
    }
    img:hover {
      transform: scale(1.2);
      transition: all 0.3s ease-in-out;
    }
    .div1 {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 100px;
    }
  </style>