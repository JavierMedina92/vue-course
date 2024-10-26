<template>
  <div> 
    <h1>Catalogo de Articulos</h1>
    <div>
        <div class="d-flex justify-content-center flex-grow-0 flex-wrap">
            <div class="card" style="width: 18rem;">
                <div class="card-body">
                    <h5 class="card-title">Cards Title</h5>
                    <h6 class="card-subtitle mb-2 text-body-secondary">Card Subtitle</h6>
                    <p class="card-text">Aqui mismo hare un bonito diseño</p>
                    <a href="#" class="card-link">Card link</a>
                    <a href="#" class="card-link">Another link</a>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            articulos: [
                {
                    codArticulo: 0,
                    descripcion: 'Articulo de Prueba',
                    precio:9999.99,
                    urlImagen: ''
                },
                {
                    codArticulo: 1,
                    descripcion: 'Articulo de Prueba1',
                    precio:9999.98,
                    urlImagen: ''
                },
                {
                    codArticulo: 2,
                    descripcion: 'Articulo de Prueba2',
                    precio:9999.97,
                    urlImagen: ''
                },
                {
                    codArticulo: 3,
                    descripcion: 'Articulo de Prueba3',
                    precio:9999.96,
                    urlImagen: ''
                }
            ]
        }
    },
    methods: {

    }
}
</script>

<style>
h1 {
    background-color: rgba(23, 8, 243, 0.884);
    color: rgb(6, 250, 6);
    font-family: Arial, Helvetica, sans-serif;
    font-size: medium;
    font-weight: bold;
}

.card-link {
    display: block;
    background-color: darkblue;
    color:rgb(8, 235, 8);
    border-radius: 5px;
    text-decoration: none;
}

.card-text {
    display: block;
    background-color: rgb(248, 244, 7);
    color: darkblue;
    border-radius: 5px;
}
</style>