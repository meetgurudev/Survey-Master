# Survey-Master
This is a android based application built for extracting the location of the user and record a image refering to that location.
* Submitting a pin.
  * User can go to intended location, can register the location co-ordinates along with an option to upload a pictiure of the current location.
    User can only upload the image using camera option provided, which means user can't upload an image of the location from directory, 
    with a tag, basically a custom name for the location and it's image.
  * While submitting, the following details are stored,
      * Location Coordinates.
      * Location tag (custom name).
      * Location Picture.
      * Existing Cluster requests.
       * Further, based on the request type, User can
        * Add the newly fetched cluster to the existing pool.
        * Identify and Modify the existing clusters in the pool.
        * Intergrade if the clusters overlapping and update the organizational geospatial pool.    
    
      
* Viewing the pins.
  * User can view all the submitted pins by clicking "View submiited locations". 
  * They are listed with the same format how it was done while uploading.
  * These pins are shown in card view structure.
  * To get the specific cluster details, on click of card view ,user will be redirected to browser window.
  
