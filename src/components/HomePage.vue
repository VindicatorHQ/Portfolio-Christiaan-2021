<template>
  <section class="container mx-auto">
    <div class="bg-gray-800 h-16">
      <h1 class="text-center pt-4 text-lg text-white font-semibold">Portfolio Website Christiaan van Haasteren</h1>
    </div>

    <article class="md:flex bg-gray-100 rounded-b-lg p-8 md:p-0">
      <img class="w-32 h-32 md:w-48 md:h-auto md:rounded-none rounded-full mx-auto" src="../assets/images/christiaan.jpg" alt="Christiaan">
      <div class="pt-6 md:p-8 text-center md:text-left space-y-4">
        <h1 class="text-lg font-semibold">
          Wie ben ik?
        </h1>

        <p class="text-lg font-semibold">
          Mijn naam is Christiaan van Haasteren, ik ben 19 jaar en ben net afgestudeerd van het MBORijnland Leiden. <br>
          Programmeren is een passie voor mij, ik leer graag veel over nieuwe talen en heb ook heel veel kennis van specifieke talen als ik er eenmaal in zit. <br>
          Hieronder ga ik dieper in op mijn vooropleiding, vaardigheden, projecten en kennis.
        </p>
      </div>
    </article>

    <article class="grid md:grid-flow-col md:grid-rows-2 md:grid-cols-2 gap-2 mt-6">
      <div class="pt-3 md:p-4 bg-gradient-to-r from-green-200 to-blue-300">
        <img class="w-60 h-auto mx-auto" src="../assets/images/mborijnland.png" alt="mborijnland logo">
        <h1 class="text-lg font-semibold text-center">
          Mijn vooropleiding
        </h1>

        <p class="font-semibold text-center mt-6">
          Ik heb een 3 jarige Applicatie en Mediaontwikkelaar opleiding gevolgd op het MBORijnland in Leiden.
          Hier heb ik de basis geleerd van websites ontwikkelen in HTML, CSS, JS, PHP, MySQL en Laravel.
          Ik heb hier ook geleerd om basis applicaties in Java te maken via de commandline en tijdens project een android app gemaakt in een groep.
        </p>
      </div>

      <div class="pt-3 md:p-4 bg-gradient-to-r from-green-200 to-blue-300">
        <h1 class="text-lg font-semibold text-center">
          Mijn projecten
        </h1>

        <div class="grid md:grid-flow-col md:grid-cols-2">
          <div>
            <h2 class="text-lg font-semibold text-center mt-2">
              DeviatorV2 Discord Bot:
            </h2>
            <p class="font-semibold text-center mt-2">
              In mijn vrije tijd spendeer ik mijn tijd aan het verder coderen/verbeteren van mijn discord chat client bot.
              De discord bot is geschreven in js, en maakt dus gebruik van de discord.js library, ik heb hier veel tijd ingestoken en doe hier ook het meeste met javascript.
            </p>
          </div>

          <div>
            <h2 class="text-lg font-semibold text-center mt-2">
              DeviatorV2 Website:
            </h2>
            <p class="font-semibold text-center mt-2">
              Voor de discord bot heb ik ook een website gemaakt, die website heeft als basis laravel en gebruikt dus het mvc model om de data op te halen van een database.
              De website maakt gebruik van Laravel 6.*, Bootstrap 4.*, Vue 2.*, deze wordt op het moment omgezet naar Tailwindcss 2.*.
            </p>
          </div>
        </div>
      </div>

      <div class="pt-3 md:p-4 bg-gradient-to-r from-blue-300 to-green-200">
        <img class="w-40 h-auto mx-auto" src="../assets/images/skills.png" alt="skills">
        <h1 class="text-lg font-semibold text-center">
          Mijn vaardigheden
        </h1>

        <p class="font-semibold text-center mt-6">
          Mijn programmeer skills liggen bij het programmeren van backend systemen in PHP.
          Ik ben sterk in het bouwen van CRUD systemen maar ook goed beveiligde log in systemen.
          Data bescherming met PHP beheers ik ook en het afhandelen van niet gecertificierde requests.
          Ik beschik over veel kennis van de PHP framework Laravel en de werkingen daarvan.
        </p>
      </div>

      <div class="pt-3 md:p-4 bg-gradient-to-r from-blue-300 to-green-200">
        <h1 class="text-lg font-semibold text-center">
          Kennis Programmeer/Scripttalen
        </h1>

        <p class="font-semibold text-center mt-6">
          Ik ben zelf heel sterk met de talen PHP en MySQL en heb veel ervaring met de PHP framework Laravel.
          Zelf codeer ik heel graag in PHP en vooral in Laravel applicaties, mijn kennis is hoog in die omgevingen omdat ik daar al meerdere projecten in heb gedaan en ook mijn grootste ervaring in heb opgedaan.
          Ik ben zelf het beste thuis in het maken van backend systemen, mijn frontend kennis is gelimiteerd en is dus ook een punt van verbeter punt van mij.
          Ik heb gewerkt met html en css (bootstrap 4, tailwind 2) maar ook javascript (vue 2/3) alhoewel ik nog veel kan leren van javascript.
        </p>

        <div class="grid grid-cols-5">
          <img class="h-20 mx-auto" src="../assets/images/html5.png" alt="html5 logo">
          <img class="h-20 mx-auto" src="../assets/images/css3.png" alt="ccs3 logo">
          <img class="h-20 mx-auto" src="../assets/images/php.png" alt="php logo">
          <img class="h-20 mx-auto" src="../assets/images/laravel.png" alt="laravel logo">
          <img class="h-20 mx-auto" src="../assets/images/mysql.png" alt="mysql logo">
        </div>
      </div>
    </article>

    <div class="bg-gray-800 h-16 mt-2">
      <h1 class="text-center pt-4 text-lg text-white font-semibold">© Christiaan van Haasteren 2021</h1>
    </div>

  </section>
</template>

<script>
export default {
  name: "HomePage"
}
</script>

<style scoped>

</style>