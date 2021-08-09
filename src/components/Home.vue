<template>
<div>
<div class="background-photo full-height bg-danger p-4">
<b-container>

<h3 class="head">Design</h3>

 <b-container class="text-center">
 <b-row>
    <b-col>
   <b-form-input v-model="value" type="search" debounce="500" placeholder="Search" icon="x">
      </b-form-input>


    </b-col>
  </b-row>
</b-container>



<div class="pt-5">
  <b-row>
    <b-col>
      <b-card-group columns>
    <b-card
      title="Card title that wraps to a new line"
      img-src="https://placekitten.com/g/400/450"
      img-alt="Image"
      img-top
    >
    
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>
      <b-card
      title="Card title that wraps to a new line"
      img-src="https://placekitten.com/g/400/450"
      img-alt="Image"
      img-top
    >
    
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>
      <b-card
      title="Card title that wraps to a new line"
      img-src="https://placekitten.com/g/400/450"
      img-alt="Image"
      img-top
    >
    
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>
     </b-card-group>
    </b-col>
  </b-row>
</div>


<div class="pt-5">
  <b-row>
    <b-col>
      <b-card-group columns>
    <b-card
      title="Card title that wraps to a new line"
      img-src="https://placekitten.com/g/400/450"
      img-alt="Image"
      img-top
    >
    
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>
      <b-card
      title="Card title that wraps to a new line"
      img-src="https://placekitten.com/g/400/450"
      img-alt="Image"
      img-top
    >
    
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>
      <b-card
      title="Card title that wraps to a new line"
      img-src="https://placekitten.com/g/400/450"
      img-alt="Image"
      img-top
    >
    
      <b-card-text>
        This is a wider card with supporting text below as a natural lead-in to additional content.
        This content is a little bit longer.
      </b-card-text>
    </b-card>
     </b-card-group>
    </b-col>
  </b-row>
</div>

  </b-container>
  </div>
  <b-container class="photo-slide pt-5">
  <b-row>
  <b-col>
 <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-width="1024"
    img-height="480"
  >
    <b-carousel-slide
      caption="First slide"
      img-src="https://picsum.photos/1024/480/?image=10"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Second Slide"
      img-src="https://picsum.photos/1024/480/?image=12"
    ></b-carousel-slide>
    <b-carousel-slide
      caption="Third Slide"
      img-src="https://picsum.photos/1024/480/?image=22"
    ></b-carousel-slide>
  </b-carousel>
  </b-col>
  </b-row>
  </b-container>

  <b-container>
  <h3>dsadas</h3>
  </b-container>


  </div>
  
</template>

<script>
export default {
      head() {
      return {
        title: 'Home'
      }
  },
}
</script>

<style scoped>
.height{
  min-height: 10rem;
  background: lightgray;
}
.background-photo {
  background: url('../assets/124.jpg')
}
.head{
      color: #ffff;
}
</style>