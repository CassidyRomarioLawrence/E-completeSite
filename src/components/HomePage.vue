<template>
    <section id="home-image">
    </section>
    <section id="home-content">
      <div class="container title">
        <div class="row">
          <h1>Welcome To SneakPeak .</h1>
          <h4>Home of Exclusive Kicks</h4>
        </div>
      </div>
      <div class="container brands py-4">
        <div class="row">
          <div class="col-sm-6 adidas">
            <h4>Adidas Collection</h4>
          </div>
          <div class="col-sm-6 vans">
            <h4>Vans Collection</h4>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4 nike">
            <h4>Nike Collection</h4>
          </div>
          <div class="col-sm-4 jordans">
            <h4>Jordan Collection</h4>
          </div>
          <div class="col-sm-4 new-balance">
            <h4>New Balance Collection</h4>
          </div>
        </div>
      </div>
    </section>
    <section id="new-releases">

    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
#home-image{
  background-image: url(https://i.postimg.cc/VNkCCHmy/glodi-miessi-ushz-Bu-B-OYY-unsplash.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 50vh;
}

.title{
  padding: 30px;
  display: flex;
  justify-content: center;
}

.row h1{
  font-weight: bold;
  font-size: 5rem;
}

.adidas,.vans,.nike,.new-balance,.jordans{
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  min-height: 50vh;
  border: 5px solid white;
  transition: transform ease 0.3s;
  cursor: pointer;
}

.adidas:hover,.vans:hover,.nike:hover,.new-balance:hover,.jordans:hover{
  transform: scale(1.1);
}

.adidas{
  background-image: url(https://i.postimg.cc/1zVmp33q/fachry-zella-devandra-b-NSd-Ik-CBJOs-unsplash.jpg);
}

.vans{
  background-image: url(https://i.postimg.cc/sxJBWggr/izz-danial-4-Ewm7-QQF-q4-unsplash.jpg);
}

.nike{
  background-image: url(https://i.postimg.cc/6pyNDWp8/sneakers123-6ha-Ngmw-VNMc-unsplash-1.jpg);
}

.jordans{
  background-image: url(https://i.postimg.cc/8PYmZZbr/albert-vincent-wu-F24c-C3-HK6-Rc-unsplash.jpg);
}

.new-balance{
  background-image: url(https://i.postimg.cc/K8r41z4v/maksim-larin-ezdrvz-A1h-Zw-unsplash.jpg);
}

.brands h4{
  color: whitesmoke;
  padding-top: 5px;
}

@media screen and (max-width: 530px){
  .row h1{
    font-size: 3rem;
  }
}
</style>