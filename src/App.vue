<template>
  <div class="h-[100] min-h-screen font-[Poppins]">
  <nav class="z-10 w-full bg-white shadow-2xl md:flex md:items-center md:justify-between">
    <div class="flex items-center justify-between">
      <span class="flex items-center text-xl font-bold hover:rotate-3 hover:cursor-pointer">
        <img class="w-16" src="https://img.freepik.com/photos-gratuite/anneau-or-luxe-pierre-violette_1203-1528.jpg?w=740&t=st=1699095555~exp=1699096155~hmac=8e58993a206ec192ddafc133e91989e99d0e46ad81b0c76b91fc3ab0818399e5" alt="img_voler" />
        Gloria-Paradise
      </span>
      <div class="md:hidden">
        <button class="mx-4 rounded-xl bg-gradient-to-t from-red-500 to-yellow-300 px-5 py-2 text-white duration-500 hover:opacity-[0.4]">Commander</button>
        <span class="mx-2 rounded-lg bg-indigo-500 px-5 py-2 text-white hover:cursor-pointer md:hidden" onclick="Menu(this)">menu</span>
      </div>
    </div>
    <div class="flex">
      <ul class="absolute left-0 top-[-400px] z-[-1] w-full bg-white py-4 pl-7 pt-10 font-[Poppins] opacity-0 transition-all ease-in md:static md:z-auto md:flex md:w-auto md:items-center md:py-0 md:pl-0 md:opacity-100">
        <li class="mx-4 duration-500 hover:text-yellow-600"><a href="#">Accueil</a></li>
        <li class="mx-4 duration-500 hover:text-yellow-600"><a href="#">Nos Colliers</a></li>
        <li class="mx-4 duration-500 hover:text-yellow-600"><a href="#">Nos Produits</a></li>
        <button class="mx-4 rounded-xl bg-gradient-to-t from-red-500 to-yellow-300 px-5 py-2 text-white duration-500 hover:opacity-[0.4]">Commander</button>
      </ul>
    </div>
  </nav>
  <div class="top-16 h-64 w-full bg-red-400">
    <img src="https://i.imgur.com/rzdOrEh.jpeg" alt="bannier" class="h-full w-full object-cover object-top" />
  </div>

  <div class="my-4 w-full font-[Poppins]">
    <span class="flex w-full justify-center text-3xl font-bold"> Qui Sommes Nous ?</span>

    <div class="min-h-[90px]: mx-auto my-5 h-64 w-[97%] rounded-lg bg-red-50 p-2 shadow-2xl">
      <img class="float-left mr-2 h-52 w-52 rounded-lg object-cover" src="https://scontent.cdninstagram.com/v/t51.29350-15/397544924_367133689073784_7439218412771679660_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=c4dd86&_nc_ohc=CIhMQOICJx0AX9RTIl4&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.cdninstagram.com&oh=00_AfBgrlILueDQMs8GTKLlG5oriHxBn5GXoNt_3Gm4nAPluw&oe=654B0F08" alt="image1" />
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Perspiciatis voluptatibus minima pariatur ullam expedita, suscipit ut a Lorem ipsr ullam expedita, suscipit ut a Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto esse illum aliquid ad incidunt, laborum fugit eius eos, facilis porro consectetur optio ipsum magni dolorem dolor recusandae dignissimos, laboriosam accusamuing elit. Architecto esse illum aliquid ad incidunt, laborum fugit eius eos, facilis porro consectetur optio ipsum magni dolorem dolor recusandae dignissimos, laboriosam accusamus.</p>
    </div>
  </div>

  <div class="mx-auto my-4 w-[96%] font-[Poppins]">
    <span class="mb-5 flex w-full justify-center text-3xl font-bold">Pourquoi Nous Faire Confiance ? </span>
      <div class="flex flex-row flex-wrap justify-between gap-10">
        <div class="h-52 w-52 rounded bg-cover bg-center shadow-2xl" style="background-image: url('https://i.imgur.com/hJlYeHi.jpeg')"></div>
        <div class="h-52 w-52 rounded bg-cover bg-center shadow-2xl" style="background-image: url('https://i.imgur.com/GfEYA30.jpg')"></div>
        <div class="h-52 w-52 rounded bg-cover bg-center shadow-2xl" style="background-image: url('https://i.imgur.com/fSq8Cpd.jpg')"></div>
        <div class="h-52 w-52 rounded bg-cover bg-center shadow-2xl" style="background-image: url('https://i.imgur.com/ZQ7KEn1.jpg')"></div>
        <div class="h-52 w-52 rounded bg-cover bg-center shadow-2xl" style="background-image: url('https://i.imgur.com/M5Qko2s.jpg')"></div>
        <div class="h-52 w-52 rounded bg-cover bg-center shadow-2xl" style="background-image: url('https://i.imgur.com/iO8b7fH.jpg')"></div>
    </div>
  </div>
  <div class="h-20 bg-slate-400 flex items-center justify-center text-xl font-bold">
    <p>This is the first Website that i developp with a framework || Created by VEMBE BETHUEL ALTAÏR - VBA</p>
  </div>
</div>
</template>


<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');
#app {
  font-family: "Poppins",sans-serif;
}
</style>
