<template>
  <div class="profile">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="media text-left">
                  <img src="../assets/logo.png" class="user-pict mr-3" alt="...">
                  <div class="media-body">
                    <h5 class="mt-0">Fana Media</h5>
                    <p>Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin.</p>
                  </div>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css"

export default {
    name: 'profile',
    components: {

    }


}
</script>

<style scoped>
.user-pict{
  border-radius: 200%;
  height: 100px;
  width: 120px;
  }


</style>