URL for CP stamps store: https://www.canadapost-postescanada.ca/shop/stamps.jsf

Page used for examples: https://www.canadapost-postescanada.ca/shop/stamps/canada/p-414165111.jsf?execution=e1s1

Information from site to include
* Item name
  * Example Structure:
```
<h3 class="itemTitle">
  NEW! PRE-ORDER Eid (2021): Permanent<sup>TM</sup> domestic rate stamps - booklet of 10
</h3>
```

* Issue date
  * Example structure
```
<tr>
  <td><b>Issue Date</b></td>
  <td>April 22, 2021</td>
</tr>
```

* Stamp designer
  * Example structure
```
<tr>
  <td><b>Stamp Designer</b></td>
  <td>Lionel Gadoury<br> Andrew Conlon <br> Brad Pyne <br>Context Creative</td>
</tr>
```

* Stamp Value
  * Example structure
```
<tr>
  <td><b>Stamp Value</b></td>
  <td>Permanent<sup>TM</sup> (domestic rate)</td>
</tr>
```

* Item price
  * Example structure
```
<h4 class="product"> <!-- isParent -->
  <strong>Product</strong>
  <input type="hidden" name="basketItems[0].itemId" value="21359">								
  <strong># 414165111</strong><br>
  <span class="largePrice">
    $9.20
  </span> <!-- !isParent &amp;&amp; priceExist -->
</h4>
```

* product number
  * Example structure
```
<h4 class="product"> <!-- isParent -->
  <strong>Product</strong>
  <input type="hidden" name="basketItems[0].itemId" value="21359">								
  <strong># 414165111</strong><br>
  <span class="largePrice">
    $9.20
  </span> <!-- !isParent &amp;&amp; priceExist -->
</h4>
```

* Stamp Dimensions
  * Example Structure
```
<tr>
  <td><b>Dimensions</b></td>
  <td>28 mm by 35 mm</td>
</tr>
```

* Stamp Quantity
  * Example structure
```
<tr>
  <td><b>Quantity Produced</b></td>
  <td>120,000</td>
</tr>
```

* Stamp image/tumbnail and product image/thumbnail
  * Exampe structure
```
<div class="productImages" id="prod_images"><div id="gallery" class="magnifyGallery">
        
		<div id="productPhoto">
	       <div style="height:216px;width:216px;" class="zoomWrapper">
             <img 
                 id="img_01" data-zoom-image="/shop/mc/assets/images/app/ecomm/large/414165111.jpg" 
                 src="/shop/mc/assets/images/app/ecomm/large/414165111.jpg" 
                 alt="NEW! PRE-ORDER Eid (2021): Permanent<sup>TM</sup> domestic rate stamps - booklet of 10" 
                 style="position: absolute; width: 216px; height: 216px;">
             <div style="background: rgba(0, 0, 0, 0) 
                 url(&quot;https://www.canadapost.ca/cpo/mc/assets/images/common/ajax-loader.gif&quot;) 
                 no-repeat scroll center center; 
                 height: 263.2px; width: 216px; z-index: 2000; 
                 position: absolute; display: none;">
             </div>
             <div style="background: rgba(0, 0, 0, 0) 
                 url(&quot;https://www.canadapost.ca/cpo/mc/assets/images/common/ajax-loader.gif&quot;) 
                 no-repeat scroll center center; 
                 height: 99px; width: 216px; z-index: 2000; 
                 position: absolute; display: none;">
             </div>
             <div style="background: rgba(0, 0, 0, 0) 
                 url(&quot;https://www.canadapost.ca/cpo/mc/assets/images/common/ajax-loader.gif&quot;) 
                 no-repeat scroll center center; 
                 height: 263.2px; width: 216px; z-index: 2000; 
                 position: absolute; display: none;">
             </div>
             <div style="background: rgba(0, 0, 0, 0) 
                 url(&quot;https://www.canadapost.ca/cpo/mc/assets/images/common/ajax-loader.gif&quot;) 
                 no-repeat scroll center center; 
                 height: 99px; width: 216px; z-index: 2000; 
                 position: absolute; display: none;">
             </div>
             <div style="background: rgba(0, 0, 0, 0) 
                 url(&quot;https://www.canadapost.ca/cpo/mc/assets/images/common/ajax-loader.gif&quot;) 
                 no-repeat scroll center center; 
                 height: 216px; width: 216px; z-index: 2000; 
                 position: absolute; display: none;">
             </div>
         </div>
     </div>

        <div id="thumbnails_2">
          <a href="#" data-image="/shop/mc/assets/images/app/ecomm/large/414165111.jpg" data-zoom-image="/shop/mc/assets/images/app/ecomm/large/414165111.jpg" class="active">
            <img id="img_01" src="/shop/mc/assets/images/app/ecomm/large/414165111.jpg" alt="NEW! PRE-ORDER Eid (2021): Permanent<sup>TM</sup> domestic rate stamps - booklet of 10" width="50px">
          </a>
          <a href="#" data-image="/shop/mc/assets/images/app/ecomm/large/414165111-3.jpg" data-zoom-image="/shop/mc/assets/images/app/ecomm/large/414165111-3.jpg" class="">
            <img id="img_01" src="/shop/mc/assets/images/app/ecomm/large/414165111-3.jpg" alt="NEW! PRE-ORDER Eid (2021): Permanent<sup>TM</sup> domestic rate stamps - booklet of 10" width="50px">
          </a>
          <a href="#" data-image="/shop/mc/assets/images/app/ecomm/large/414165111-2.jpg" data-zoom-image="/shop/mc/assets/images/app/ecomm/large/414165111-2.jpg" class="">
            <img id="img_01" src="/shop/mc/assets/images/app/ecomm/large/414165111-2.jpg" alt="NEW! PRE-ORDER Eid (2021): Permanent<sup>TM</sup> domestic rate stamps - booklet of 10" width="50px">
          </a>
        </div>
    </div>
</div>
```


Things I want to include but will ahve a harder time deriving since they don't seem to have a consistant data field:
* number of stamps in product 
  * included in the title but may not be consistant
* Format of product
  * a booklet but titling may not be consistant
* Layout and dimensions of stamps in format
  * this may not be possible
