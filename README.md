# Ruthless_Launcher

adding as an system app

# Make Directory

cd packages/apps
mkdir Ruthless_Launcher
cd Ruthless_Launcher

# Clone the git

git clone  

# Adding the app package in your device tree

cd
cd <working_directory>/device/<manufacturer>/<device_codename>
nano device.mk
 
# ADD THIS LINE BELOW IT 

PRODUCT_PACKAGES += \
  Ruthless_Launcher

# Compile and good to go... Enjoy!!!
