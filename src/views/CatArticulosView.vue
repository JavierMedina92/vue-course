<template>
  <div> 
    <h1>Catalogo de Articulos</h1>
    <div>
        <div class="d-flex justify-content-center flex-grow-0 flex-wrap">
            
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
                    precio:9999.99,
                    urlImagen: ''
                },
                {
                    codArticulo: 2,
                    descripcion: 'Articulo de Prueba2',
                    precio:9999.99,
                    urlImagen: ''
                },
                {
                    codArticulo: 3,
                    descripcion: 'Articulo de Prueba3',
                    precio:9999.99,
                    urlImagen: ''
                }
            ]
        }
    },
    methods:{

    }
}
</script>

<style>

</style>