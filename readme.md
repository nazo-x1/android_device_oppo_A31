# android_device_oppo_A31

the android device soure for oppo A31/A31t 2015 (OPPO_15005) for twrp build

success build with https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni on branch twrp-5.1

if not display, try replace (all the) `msm_mdp.h` file in path `bootable/recovery` with 
https://github.com/oppo-source/R7f-4.4-kernel-source/blob/master/include/uapi/linux/msm_mdp.h, it shoud works
