# Image Sizing

Huddles CMS will accept the upload of any sized image. _For example_ a _**2000 x 4000px** image._

In order to get content to fit nicely on your static pages, you first need to understand aspect ratios and how this will affect how your image will be rendered. 

## Understanding Aspect ratios

An aspect ratio is a proportional relationship between an image's width and height. Essentially, it describes an image's shape.

Aspect ratios are written as a formula of width to height, like this: **3:2**.

For example, is an image has an aspect ratio of 1:1, since the height and width are the same. The image could be 500px × 500px, or 1500px × 1500px, and the aspect ratio would still be 1:1.

As another example, a portrait-style image might have a ratio of 2:3. With this aspect ratio, the height is 1.5 times longer than the width. So the image could be 500px × 750px, 1500px × 2250px, etc. 

## Aspect Ratios and Huddle 

Aspect ratios are important as Huddle implements reponsive web design to its platfrom. 

* Because images scale up or down to fit different browser widths, they don't have exact dimensions \(like 750px × 500px\), but will always be the same shape. This shape will be determined of the images aspect ratio. 
* In huddle, Images within the page boundary \(e.g. the white background\) will automatically scale in **width** to fit across the whole width of this area.
* Images with an aspect ratios that have a larger height value will appear very large down the page and may look unprofessional.

In order to fix this you should crop your images to the correct aspect ratio **before** uploading to the CMS. 

![](../../.gitbook/assets/image%20%283%29.png)

![](../../.gitbook/assets/image%20%284%29.png)

![](../../.gitbook/assets/image%20%286%29.png)

