aokp device tree

How to build aokp for codinalte 

1 first you have to download the device tree then kernel 


 
2 then after you have the device tree and kernel in place you need vendor file
 



3 in device tree is a folder call product file that file go in aokp build in folder vendor/aokp/products then you have to find the file vendorsetup.sh in vendor/aokp then in there you add this line in bottom or the top add_lunch_combo aokp_codinalte-userdebug then go in to vendor/aokp/products folder and find Androidproducts.mk file and add this line $(LOCAL_DIR)/codinalte.mk bottom or top it don't matter then go in to device tree folder and copy the file pull then paste in aokp folder source that there you see all the files in build or repo.



4 the start commands first do the . pull command in terminal that will download all the patchs for system for build then do the command . build/envsetup.sh && brunch codinalte to start build and make clobber if is any error the stop build good luck lol
