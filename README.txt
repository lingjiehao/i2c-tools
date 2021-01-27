# i2c-tools

源码在https://i2c.wiki.kernel.org/index.php/I2C_Tools中的
https://mirrors.edge.kernel.org/pub/software/utils/i2c-tools/下载, 
未经说明表示没有对源码修改.

当包含Android.mk时,表示可以直接放在Android源码中编译, 我喜欢放在external目录下.

```bash
source build/envsetup.sh
lunch xxx-userdebug

cd external/i2c-tools
mm -j8
```

编译结果在out的system/bin下
