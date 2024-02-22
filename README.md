# proprietary_vendor_oplus_camera

Prebuilt stock oplus Camera to include in custom ROM builds.

### How to use?

1. Clone this repo to `vendor/oplus/camera`

2. Inherit it from `device.mk` in device tree:

```
# Camera
$(call inherit-product-if-exists, vendor/oplus/camera/opluscamera.mk)
```

3. Ensure that the PRODUCT_BRAND is either oneplus or oppo or realme and that it is not overriden by any of the safetynet hacks.
