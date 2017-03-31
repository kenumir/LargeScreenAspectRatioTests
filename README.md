# LargeScreenAspectRatioTests

## Variant 1 - default project setup:
* No meta-data android:name="android.max_aspect"
* No android:resizeableActivity

[Variant 1](https://raw.githubusercontent.com/kenumir/LargeScreenAspectRatioTests/master/screens/variant1.png)

## Variant 2 - set max_aspect
* Set meta-data `android:name="android.max_aspect" android:value="1.86"`
* No android:resizeableActivity

[Variant 2](https://raw.githubusercontent.com/kenumir/LargeScreenAspectRatioTests/master/screens/variant2.png)

Black stripes over nad under screen should be visible, like on first screen of this image: 
https://2.bp.blogspot.com/-z90WXVMtGsk/WNvh_iWyfKI/AAAAAAAAD-Y/rFzFhaYS7t89nX8byw9e1_q0nMOgkpZNgCLcB/s1600/image00.png
Nothing, no black stripes

## Variant 3
* Set meta-data `android:name="android.max_aspect" android:value="1.86"`
* Set android:resizeableActivity=false

[Variant 3](https://raw.githubusercontent.com/kenumir/LargeScreenAspectRatioTests/master/screens/variant3.png)

## Variant 4
* Set meta-data `android:name="android.max_aspect" android:value="1.86"`
* Set android:resizeableActivity=true

[Variant 4](https://raw.githubusercontent.com/kenumir/LargeScreenAspectRatioTests/master/screens/variant4.png)

## Variant 5
* Set meta-data `android:name="android.max_aspect" android:value="2.1"`
* Set android:resizeableActivity=true

[Variant 5](https://raw.githubusercontent.com/kenumir/LargeScreenAspectRatioTests/master/screens/variant5.png)


All screens is identical, maybe i forgot something, but from my knowledge it follows that one or two screens should have black stripes on top and bottom.