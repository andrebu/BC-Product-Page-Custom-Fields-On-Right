BC-Product-Page-Custom-Fields-On-Right-For-BigCommerce
======================================================

BC Product Page Custom Fields On Right For BigCommerce - this will show custom field 1 and 2 on the right, in the product details section.

##Installation

     Basically just need to place the link to the ProductDetails panel in the ProductWarranty panel.

##HTML
```HTML
<!-- Panels/ProductWarranty.html -->

<div class="Block Moveable Panel" id="ProductWarranty">
<!--    <h3 class="subtitle" id="videos">%%LNG_ProductWarranty%%</h3> -->
<!--    <h3 class="subtitle" id="videos">Features</h3> -->
    <div class="JointSizeHeightContainer">
<!--        Panel.JointSizeHeightPanel -->
        %%Panel.ProductOtherDetails%%
    </div> <!-- END JointSizeHeightContainer --> 
    <div class="clear"></div>
    <div class="ProductWarrantyContainer prodAccordionContent" style="display:none;">
<!--        <p>%%GLOBAL_ProductWarranty%%</p> -->
        %%GLOBAL_ProductWarranty%% 
    </div>
</div>
```

## Using

To get this to work, you just need to require the module once per run-time, like so.

    Just install and it'l do the work for you!


## Other BigCommerce modules

* [BigCommerce Product Page Demo Videos](https://github.com/iamandrebulatov/BC-Product-Page-Demo-Videos)
* [BigCommerce Product Page Brand Descriptions](https://github.com/iamandrebulatov/BC-Product-Page-Brand-Descriptions)
* [BigCommerce Product Page Brand Logos](https://github.com/iamandrebulatov/BC-Product-Page-Brand-Logos)
* [BigCommerce Product Page Custom Fields On Right](https://github.com/iamandrebulatov/BC-Product-Page-Custom-Fields-On-Right)
* [BigCommerce Category Page Color Swatch](https://github.com/iamandrebulatov/BC-Category-Page-Color-Swatch)
* [BigCommerce Category Page 2nd Alternate Thumbnail](https://github.com/iamandrebulatov/BC-Category-Page-2nd-Alternate-Thumbnail)
* [BigCommerce Category Page Videos](https://github.com/iamandrebulatov/BC-Category-Page-Demo-Videos)
* [BigCommerce Category Page Out of Stock Ribbons](https://github.com/iamandrebulatov/BC-Category-Page-Out-of-Stock-Items)


## Support

> ⚐ Please help me spend more time developing and maintaining awesome modules like this by donating!

The absolute best thing to do is to sign up with [ChangeTip](//changetip.com) or [GratiPay](//gratipay.com) if you haven't already and donate just $1 a week. That is roughly a cup of coffee per month. Also, please do donate to many other amazing open source projects!

[![ChangeTip donate button](http://andrebulatov.com/wp-content/uploads/tipme_button.png)](//www.changetip.com/tipme/andre.bulatov/ "Donate once-off to this project using ChangeTip")
[![GratiPay donate button](http://andrebulatov.com/wp-content/uploads/gratipay-button.png)](//www.gratipay.com/andrebulatov/ "Donate once-off to this project using GratiPay")


## License

The MIT License (MIT)

Copyright (c) 2014 Andre Bulatov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
