# Overlay-builder
Using Github Actions to build device specific overlays for Phh based GSI's 

## How to use
1. Fork [vendor_hardware_overlay](https://github.com/phhusson/vendor_hardware_overlay) and make the necessary changes.
2. Fork [this repo](https://github.com/Johx22/Overlay-builder)
3. Click on Actions tab. Under workflows click Overlay
4. Click Run Workflow. 
5. In FORK_URL input the URL of vendor_hardware_overlay which was forked to your Github Repositories
6. In PACKAGE_NAME input the name of LOCAL_PACKAGE_NAME from Android.mk of your Device Overlay folder and add .apk at the end. (For eg: treble-overlay-oppo-a54.apk)
7. After filling everything click Run Workflow
8. Once the building is done just refresh the page and you will be able to see your overlay which you can download right away.
