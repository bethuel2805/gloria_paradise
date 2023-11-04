<template>  
    <nav class="bg-white md:flex md:items-center md:justify-between font-[Poppins] fixed z-[10] shadow-md w-full">
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
</template>