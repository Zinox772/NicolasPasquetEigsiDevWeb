<svelte:head>
	<title>adadas Site Officiel France</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/css/bootstrap.min.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/2.0.1/css/ionicons.min.css">
</svelte:head>

<main>

	<section class="grid-wrap">
		<div class="soustitre grid-col col-12">
			<h2> BOUTIQUE HOMME</h2>
		</div>

		<div class="texte texte1 grid-col col-3 med-4 sml-6 xs-12">
			<h3>Sweat-shirt</h3>
			<div class="bestseller">
				<a href="/sweathomme"><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/sweatd.jpg"
					 height="300" width="340" onmouseover="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/sweat.jpg';"
					 onmouseout="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/sweatd.jpg'"
					 alt="" /></a>
			</div>
		</div>

		<div class="texte texte2 grid-col col-3 med-4 sml-6 xs-12">
			<h3>T-shirt</h3>
			<div class="bestseller">
				<a href="/tshirthomme"><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/tshirtd.jpg"
					 height="300" width="340" onmouseover="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/tshirt.jpg';"
					 onmouseout="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/tshirtd.jpg'"
					 alt="" /></a>
			</div>
		</div>

		<div class="texte texte3 grid-col col-3 med-4 sml-6 xs-12">
			<h3>Pantalons</h3>
			<div class="bestseller">
				<a href="/pantalonhomme"><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/pantalond.jpg"
					 height="300" width="340" onmouseover="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/pantalon.jpg';"
					 onmouseout="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/pantalond.jpg'"
					 alt="" /></a>
			</div>
		</div>

		<div class="texte texte4 grid-col col-3 med-4 sml-6 xs-12">
			<h3>Chaussures</h3>
			<div class="bestseller">
				<a href="/chaussurehomme"><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/ozweego.jpg"
					 height="300" width="340" onmouseover="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/ozweegod.jpg';"
					 onmouseout="this.src='https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/ozweego.jpg'"
					 alt="" /></a>
			</div>
		</div>
	</section>

	<section class="grid-wrap">

		<div class="soustitre grid-col col-12">
			<h2> POUR QUI FAIS-TU TES ACHATS</h2>
		</div>

		<div class="texte texte1 grid-col col-3 med-4 sml-6 xs-12">
			<h3>Femmes</h3>
			<div class="bestseller">
				<a href="/femme"><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/femmes.jpg"></a>
			</div>
		</div>

		<div class="texte texte2 grid-col col-3 med-4 sml-6 xs-12">
			<h3>Hommes</h3>
			<div class="bestseller">
				<p><a href="/homme"><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/hommes.jpg" /></a></p>
			</div>
		</div>

		<div class="texte texte3 grid-col col-3 med-4 sml-6 xs-12">
			<h3>Enfants</h3>
			<div class="bestseller">
				<p><a href="/enfant"><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/enfants.jpg" /></a></p>
			</div>
		</div>


		<div class="texte texte4 grid-col col-3 med-4 sml-6 xs-12">
			<h3>Sports</h3>
			<div class="bestseller">
				<p><img src="https://zypjedbvymdgbzcwwqgo.supabase.co/storage/v1/object/public/images/Homme/sports.jpg" /></p>
			</div>
		</div>

	</section>
</main>

<style>
  /* CSS Document */
  * {
    padding: 0;
    box-sizing: border-box;
  }
  img {
    max-width: 100%;
  }

  /*------------------------------------------------------------------------------------------------------------------------------------------------------------------------------*/
  div.soustitre {
    text-align: center;
  }
  /*------------------------------------------------------------------------------------------------------------------------------------------------------------------------------*/
  h2 {
    color: black;
    display: inline-block;
    font-size: 1.5rem;
    font-weight: normal;
    font-family: Arial;
    letter-spacing: 1px;
    font-weight: Bold;
    padding: 20px;
  }
  /*------------------------------------------------------------------------------------------------------------------------------------------------------------------------------*/
  .texte {
    text-align: center;
    font-size: 1rem;
    font-weight: normal;
    font-family: Arial;
    letter-spacing: 1px;
    padding: 15px;
  }
  .texte1 {
    background-color: #11ffee00;
    color: black;
  }
  .texte2 {
    background-color: #11ffee00;
    color: black;
  }
  .texte3 {
    background-color: #11ffee00;
    color: black;
  }
  .texte4 {
    background-color: #11ffee00;
    color: black;
  }
  .bestseller:hover {
    box-shadow: 10px 10px lightgrey;
    border: 2px solid #666;
  }

  .grid-wrap {
    display: flex;
    flex-wrap: wrap;
  }
  .grid-col {
    box-sizing: border-box;
    margin: 0;
    flex: 0 1 auto;
  }

  .col-3 {
    width: 25%;
  }
  @media only screen and (max-width: 799px) {
    .med-4 {
      width: 33.3333%;
    }
  }
  @media only screen and (max-width: 599px) {
    .sml-6 {
      width: 50%;
    }
  }
  @media only screen and (max-width: 479px) {
    .xs-12 {
      width: 100%;
    }
  }
</style>
