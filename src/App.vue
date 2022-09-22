<template>
  <Header>
    <a class="navbar-brand" href="#">FoodFraM</a>
    <template #grupo>
      <a class="nav-link" href="#">Federico Francisco Manuel 10° A</a>
    </template>
  </Header>

  <h1>Comida Rápida</h1>
  
  <CardProducto url="https://images.pexels.com/photos/1633578/pexels-photo-1633578.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Hambueguesa de Pollo" desc="Hamburguesa sencilla con carne de pollo" precio="$ 35"/>
  <CardProducto url="https://images.pexels.com/photos/708587/pexels-photo-708587.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" nombre="Pizza de Peperoni" desc="Pizza relleno de queso con peperoni Mediano" precio="$ 99"/>
  <CardProducto url="https://images.pexels.com/photos/1209029/pexels-photo-1209029.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Sánchiw Sencillo" desc="Sencillo con jamón de pavo" precio="$ 25"/>
  <CardProducto url="https://images.pexels.com/photos/1633525/pexels-photo-1633525.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Baget de Pollo" desc="Con carnde de pollo 125 G." precio="$ 45"/>
  <CardProducto url="https://images.pexels.com/photos/7390/pexels-photo.jpg?auto=compress&cs=tinysrgb&w=600" nombre="Croissant de Jamón" desc="En presentación individual" precio="$ 30"/>
  <CardProducto url="https://images.pexels.com/photos/115740/pexels-photo-115740.jpeg?auto=compress&cs=tinysrgb&w=600" nombre="Papas a la Fransesa" desc="Orden de papas a la francesa con preparación al gusto" precio="$ 25"/>

  <Footer>
    <div class="card-header">
            Universidad Tecnológica de Tehuacán
    </div>
  </Footer>

</template>

<script>
import CardProducto from './components/CardProducto.vue';
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

  export default{
    components: { CardProducto, Header, Footer, },
  };
</script>