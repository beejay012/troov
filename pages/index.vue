<template>
  <div>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <img src="../assets/logo.png" alt="logo troov" width="200" height="75">
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">

      <li class="nav-item active">
        <a class="nav-link" href="/connexion" onClick="/connexion">Connexion <span class="sr-only">(current)</span></a>
      </li>

      <li class="nav-item">
        <a class="nav-link" href="/inscription">Inscription</a>
      </li>

      <li class="nav-item">
        <a class="nav-link" href="/add">Ajouter un objet</a>
      </li>
  
      <li class="nav-item">
        <a class="nav-link" href="/lists">Liste des Objets</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="/modify">Modifier/Supprimer un Objet</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
  </div>
</template>

<style>

</style>
