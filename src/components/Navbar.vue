<template>
  <div>
    <b-navbar
      toggleable="lg"
      type="dark"
      variant="dark"
      class="border-bottom border-success border-5"
    >
      <div class="container rounded">
        <b-navbar-brand href="#" class="d-flex align-items-center"
          ><img
            alt="Vue logo"
            src="../assets/logo.png"
            width="30"
            class="mr-2"
          /><span class="fw-bold styleCustom"
            >NAS Restaurant</span
          ></b-navbar-brand
        >

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- <b-navbar-nav class="mr-auto">
            <b-nav-item href="#">Link</b-nav-item>
          </b-navbar-nav> -->

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-item href="#">
              <router-link to="/" class="nav-link"
                >Home</router-link
              ></b-nav-item
            >
            <b-nav-item href="#">
              <router-link to="/food" class="nav-link"
                >Food</router-link
              ></b-nav-item
            >
            <b-nav-item href="#">
              <router-link to="/about-us" class="nav-link"
                >About Us</router-link
              ></b-nav-item
            >
            <b-nav-item href="#">
              <router-link to="/contact-us" class="nav-link"
                >Contact Us</router-link
              ></b-nav-item
            >

            <b-nav-item href="#">
              <router-link to="/keranjang" class="nav-link">
                <b-icon-bag></b-icon-bag
                ><span class="badge badge-warning ml-2">0</span></router-link
              ></b-nav-item
            >
            <!-- <b-nav-form>
            <b-form-input
              size="sm"
              class="mr-sm-2"
              placeholder="Search"
            ></b-form-input>
            <b-button size="sm" class="my-2 my-sm-0" type="submit"
              >Search</b-button
            >
          </b-nav-form> -->

            <!-- <b-nav-item-dropdown text="Lang" right>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown> -->

            <!-- Using 'button-content' slot -->
            <!-- <b-nav-item-dropdown right>
              <template #button-content>
                <em>User</em>
              </template>
              <b-dropdown-item href="#">Profile</b-dropdown-item>
              <b-dropdown-item href="#">Sign Out</b-dropdown-item>
            </b-nav-item-dropdown> -->
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>

<!-- eslint-disable vue/multi-word-component-names -->
<script>
export default {
  name: 'Navbar',
}
</script>

<style></style>
