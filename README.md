# NNav: Off-Canvas Navigation

NNav is a lightweight framework to create a mobile inspired sidebar navigation
that slides in from the left, much like the native Facebook app.

### Getting Started

In order to be able to use Nnav within your website you need to:
 1. Load Dependencies
 2. Integrate NNav HTML Structure

#### Load Dependecies
The following files need to be added to your website to be able to use NNav.
    
````HTML
<link rel="stylesheet" href="./css/nnav.css" type="text/css" />

<script src="//ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>
<script type="text/javascript" src="./js/nnav.jquery.js"></script>
````

#### HTML Structure
````HTML

 <div class="nnav" id="nnav">
      
      <div class="nnav-nav">
        <div class="nnav-nav-inner">
        	Navigation
        </div>
      </div>
      
      <div class="nnav-content">
         <div class="nnav-content-inner">
           
          <!-- Link to Toggle Navigation -->
          <a href="#nnav" data-toggle="nnav" class="nnav-btn">
          	+
          </a>
           
          <!-- Your Content -->
          ...
          <!-- End of Your Content -->
           
        </div>
      </div>
      
    </div>

````