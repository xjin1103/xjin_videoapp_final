# xjin_videoapp_final

## Assignment Requirements
1. Use Vue.js to update your view(s) with data and event binding. Explore components and client-side routing, should you wish to include more advanced Vue.js functionality.
---------------------
2. Each individual audio / video “page” (or view) should include reviews, ratings, movie details (director, year, genre, synopsis etc) including controls to add a new rating or review. The interactive elements should be handled by Vue.js - when a user adds a comment or a review/rating, update your view with Vue.js methods / data. Update the database with an AJAX call using the fetch API, or explore Axios with Vue.js.
--------------------
3. Filter through categories and display all of the selections available (load and play a default for each). Clicking on a thumbnail should load and play that video and show its details - for example its rating, reviews / starred reviews, as well as active social media icons.


## Detailed Requirements
1. Update the folder structure for the application (refer to class examples).
2. Use Vue.js for front-end data and method binding.
3. Retrieve, populate and update reviews, ratings and social media to and from a database / view using the mysql module, Vue.js and AJAX
4. Load and play video on a thumbnail click with bound events; show that video’s details page with reviews, stars, functional social media icons etc (populate these with reactive Vue data)
5. Update your repo / detailed readme. Your master branch will be the base build; we will be adding branches based on modules and functionality.


## Dependency
1. sass
npm install -g sass

2. vue-social-sharing
npm install --save vue-social-sharing

Add HTML link <script src="/dist/vue-social-sharing.min.js"></script>

<social-sharing url="https://vuejs.org/" inline-template>
  <div>
    <network network="facebook">
      <i class="fa fa-fw fa-facebook"></i> Facebook
    </network>
    <network network="googleplus">
      <i class="fa fa-fw fa-google-plus"></i> Google +
    </network>
    <network network="linkedin">
      <i class="fa fa-fw fa-linkedin"></i> LinkedIn
    </network>
    <network network="pinterest">
      <i class="fa fa-fw fa-pinterest"></i> Pinterest
    </network>
    <network network="reddit">
      <i class="fa fa-fw fa-reddit"></i> Reddit
    </network>
    <network network="twitter">
      <i class="fa fa-fw fa-twitter"></i> Twitter
    </network>
    <network network="vk">
      <i class="fa fa-vk"></i> VKontakte
    </network>
    <network network="weibo">
      <i class="fa fa-weibo"></i> Weibo
    </network>
    <network network="whatsapp">
      <i class="fa fa-fw fa-whatsapp"></i> Whatsapp
    </network>
  </div>
</social-sharing>
