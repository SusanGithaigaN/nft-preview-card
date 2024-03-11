<template>
  <div class="card shadow-2xl w-96 overflow-hidden rounded-lg">
    <div class="p-4">
      <a href="#">
        <img
          class="object-cover rounded-xl h-80 w-full"
          src="../../images/image-equilibrium.jpg"
          alt="card 1"
        />
      </a>
    </div>

    <div class="px-4">
      <h1 class="white-txt font-bold py-2 text-2xl">Equilibrium #3429</h1>
      <p class="soft-blue py-2">Our equilibrium collection promotes balance and calm.</p>

      <div class="flex flex-col sm:flex-row py-2">
        <div class="left w-full">
          <div class="flex items-center py-4">
            <img
              class="rounded-full inline-block mr-2"
              src="../../images/icon-ethereum.svg"
              alt="Avatar"
            />
            <h5 class="text-sm">
              <span class="cyan font-semibold">0.041ETH</span>
            </h5>
          </div>
        </div>

        <div class="right w-full">
          <div class="flex items-center py-4">
            <img
              class="rounded-full inline-block mr-2"
              src="../../images/icon-clock.svg"
              alt="Avatar"
            />
            <h5 class="text-sm">
              <span class="soft-blue font-semibold">3 days left</span>
            </h5>
          </div>
        </div>
      </div>

      <hr class="text-gray-200"/>

      <div class="flex items-center py-4 font-semibold">
        <img
          class="h-10 w-10 rounded-full inline-block mr-2 border-2 border-white"
          src="../../images/image-avatar.png"
          alt="Avatar"
        />
        <h5 class="text-sm">
          <span class="soft-blue mr-2">Creation of</span>
          <span class="text-white">Jules Wyvern</span>
        </h5>
      </div>
    </div>
  </div>

  <div class="attribution py-4">
    Challenge by
    <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
      >Frontend Mentor</a
    >. Coded by <a href="https://github.com/SusanGithaigaN">Susan Githaiga</a>.
  </div>
</template>

<script></script>

<style scoped>
/* Feel free to remove these styles or customise in your own stylesheet 👍  */
.attribution {
  font-size: 11px;
  text-align: center;
  color: white;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}

.card {
  background-color: hsl(216, 50%, 16%);
}
.white-txt {
  color: hsl(0, 0%, 100%);
}
.soft-blue {
  color: hsl(215, 51%, 70%);
}
.cyan {
  color: hsl(178, 100%, 50%);
}
p {
  font-size: 18px;
}
hr{
    /* color: gray; */
    
}
</style>
