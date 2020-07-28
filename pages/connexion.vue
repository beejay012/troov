<template>
    <div>   
        <!--Barre de Navigation-->
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
        <a class="nav-link" href="add">Ajouter un objet</a>
      </li>
  
      <li class="nav-item">
        <a class="nav-link" href="lists">Liste des Objets</a>
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

        <!-- Formulaire -->
        <form>

  <div class="form-group">
    <label for="exampleInputEmail1">Adresse Mail : </label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
  </div>

  <div class="form-group">
    <label for="exampleInputPassword1">Mot de Passe :</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>

  <div class="form-group form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Se rappeler de moi</label>
  </div>

  <button type="submit" class="btn btn-primary">Connexion !</button>

</form>
    </div>
</template>

<style scoped>

</style>