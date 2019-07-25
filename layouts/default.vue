<template>
  <div>
    <header>
      <div class="head">
        <div class="logo">
          <a href="#"><img src="~assets/image/icon.png"></a>
          <div class="title">
            <h4>Foundations</h4>
            <p>Startup Landing Template</p>
          </div>
        </div>
        <div class="menu">
          <ul> 
            <li class="active">
              <a href="/" class="sub-menu">Home</a>
            </li>
            <li><a href="#" class="sub-menu">Stories</a></li>
            <li><a href="/additional" class="sub-menu">Additional Home</a></li>
            <li><a href="#" @mouseover="openDropdownMenu()" @mouseleave="openDropdownMenu()" class="sub-menu with-dropdown">Libraries</a></li>
            <li>
              <a href="#" class="btn primary get-started">Get Started</a>
            </li>
          </ul>
          <div class="dropdown" v-show="dropdownMenu">
            <div class="columns">
              <div class="column active">
                <h1>Acquire Users</h1>
                <p>Work with the tools and services you use.</p>
              </div>
              <div class="column">
                <h1>Engage Customers</h1>
                <p>Get started with our simple snippet of JavaScript.</p>
              </div>
            </div>
            <div class="columns">
              <div class="column">
                <h1>Book Appointments</h1>
                <p>We offer measures like 2FA to ensure the safety.</p>
              </div>
              <div class="column">
                <h1>Generate Leads</h1>
                <p>Become a better designer by learning this courses.</p>
              </div>
            </div>   
          </div>
        </div>
      </div>
    </header>
    <nuxt />
    <section class="section-footer">
      <div class="columns">
        <div class="column left-content">
          <div class="logo">
            <a href="#"><img src="~assets/image/icon.png"></a>
            <div class="title">
              <h4>Foundation</h4>
              <p>Startup Landing Template</p>
            </div>
            <div class="description">
              <p>Foundation is a website template for startups and small teams. It helps to build a website in no time.</p>
            </div>
            <div class="download">
              <img src="~assets/image/appstore.png">
              <img src="~assets/image/googleplay.png">
            </div>
          </div>
        </div>
        <div class="column is-three-fifths right-content">
          <div class="columns">
            <div class="column">
              <div class="menu">
                <h1>Product</h1>
                <ul>
                  <li><a href="#">Acquire Users</a></li>
                  <li><a href="#">Content Marketing</a></li>
                  <li><a href="#">Website Templates</a></li>
                  <li><a href="#">Customer Management</a></li>
                  <li><a href="#">Virtual Inbox</a></li>
                </ul>
              </div>
            </div>
            <div class="column">
              <div class="menu">
                <h1>Company</h1>
                <ul>
                  <li><a href="#">About Foundation</a></li>
                  <li><a href="#">Brand Guidelines</a></li>
                  <li><a href="#">Press Kit</a></li>
                  <li><a href="#">Support</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="columns end-footer">
        <div class="column left-content">
          <ul>
            <li><a href="#">Terms</a></li>
            <li><a href="#">Privacy</a></li>
            <li><a href="#">License</a></li>
          </ul>
        </div>
        <div class="column right-content">
          <div class="is-pulled-right">
            <ul>
              <li><a href="#"><img src="~assets/image/icon-fb.png"></a></li>
              <li><a href="#"><img src="~assets/image/icon-twitter.png"></a></li>
              <li><a href="#"><img src="~assets/image/icon-linkedIn.png"></a></li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'header',
  data() {
    return {
      dropdownMenu: false
    }
  },
  methods: {
    openDropdownMenu() {
      this.dropdownMenu = !this.dropdownMenu
    }
  }
}
</script>
