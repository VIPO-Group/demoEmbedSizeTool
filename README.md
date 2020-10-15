## Embed sizetool in an existing web site

For this example, I juste use [bootstrap4](https://getbootstrap.com/). 

You can directly embed sizetool in integrating the following code. 

I projet an example here. 

```html
    <div class="text-center">
        <button type="button" class="btn btn-secondary" data-toggle="modal" data-target="#modalSizeTool">SizeTool</button>
      </div>
      
      <div class="modal fade" id="modalSizeTool" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog modal-lg" role="document" style="height: 800px;width: 300px">
      
          <!--Content-->
          <div class="modal-content">
      
            <!--Body-->
            <div class="modal-body mb-0 p-0" style="height: 800px;width: 200px">
      
              <!--SizeTool-->
              <div id="map-container-google-2" class="z-depth-1-half map-container" style="height: 800px;width: 200px">
                <iframe src="https://sizetool.vipogroup.com" frameborder="0" 
                  style="border:0;height: 800px" allowfullscreen></iframe>
              </div>
      
              <!--SizeTool-->
      
            </div>
      
            <!--Footer-->
            <div class="modal-footer justify-content-center">
      
              <button type="button" class="btn btn-outline-primary btn-md" data-dismiss="modal">Close <i class="fas fa-times ml-1"></i></button>
      
            </div>
     
          </div>
          <!--/.Content-->
      
        </div>
      </div>
```