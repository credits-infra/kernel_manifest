# Kernel manifest for xiaomi sm8350 devices

## Get Started

Use this command to build

```bash
BUILD_CONFIG=kernel/msm-5.4/build.config.msm.lahaina VARIANT=qgki LTO=thin DEVICE=renoir BUILD_KERNEL=1 build/build.sh | tee build.log
```

The ```DEVICE``` var can be modified by yourself but please make sure you've added support for your target device. Here is a [reference commit](https://github.com/EndCredits/android_kernel_xiaomi_sm8350/commit/299d41a79c2d1e9bd74d645b52696a1046438441)
