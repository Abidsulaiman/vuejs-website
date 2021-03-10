<template>
    
  

  <section class="features" id="features">
    <div class="container">
      <div class="section-heading text-center">
        <h2>Unlimited Features, Unlimited Fun</h2>
        <p class="text-muted">Check out what you can do with this app theme!</p>
        <hr>
      </div>
      <div class="row">
        <div class="col-lg-4 my-auto">
          <div class="device-container">
              <img src="https://desktopsolutions.com/wp-content/uploads/2015/03/iPhone-6-47-inch-Three-colors-Mockup.png" class="img-fluid" alt="">
          </div>
        </div>
        <div class="col-lg-8 my-auto">
          <div class="container-fluid">
            <div class="row">
              <div class="col-lg-6" v-for="(item, key) in featuresJson" :key="key">
                <div class="feature-item">
                  <i :class="`text-primary fa ${item.icon}`"></i>
                  <h3>{{item.title}}</h3>
                  <p class="text-muted">{{item.subtitle}}</p>
                </div>
              </div>
            </div>          
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'Features',
    data: () => ({
      featuresJson: [
        {
          icon: 'fa-phone',
          title: 'Device Mockups',
          subtitle: 'Ready to use HTML/CSS device mockups, no Photoshop required!'
        },
        {
          icon: 'fa-camera',
          title: 'Flexible Use',
          subtitle: 'Put an image, video, animation, or anything else in the screen!'
        },
        {
          icon: 'fa-gift',
          title: 'Flexible Use',
          subtitle: 'Put an image, video, animation, or anything else in the screen!'
        },
        {
          icon: 'fa-unlock',
          title: 'Flexible Use',
          subtitle: 'Put an image, video, animation, or anything else in the screen!'
        }
      ]
    })
}
</script>