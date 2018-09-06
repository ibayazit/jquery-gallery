# jquery-gallery
a gallery script with using jQuery

##### Sample image with using bootstrap 4 cards
![](picture1.png)
##### Sample image with data-text
![](picture2.png)
##### Sample image without data-text
![](picture3.png)

# How to use
```html
<div class="container py-4">
  <div class="row">
    <div class="col-12">
      <!-- gallery class need for using gallery -->
      <div class="card-columns gallery">
        <!-- need a div for contains img tag -->
        <div class="galleryItem card">
          <!-- just need a img tag. if you are want a text add data-text-->
          <img class="card-img-top" src="assets/images/p1.jpeg">
        </div>
      </div>
    </div>
  </div>
</div>  
```
and add your page main.css and main.js
