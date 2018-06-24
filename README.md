# my_error_adn_soln


*******************************************************************************************************************************
[  3% 95/2775] Building Kernel Headers
FAILED: /home/sathishpremabai/lineage/out/target/product/lux/obj/KERNEL_OBJ/.headers_install_deps 
/bin/bash -c "(rm -f /home/sathishpremabai/lineage/out/target/product/lux/obj/KERNEL_OBJ/.headers_install_deps ) && (make -j4  CFLAGS_MODULE=\"-fno-pic\" -C kernel/motorola/ms
m8916 O=/home/sathishpremabai/lineage/out/target/product/lux/obj/KERNEL_OBJ ARCH=arm CROSS_COMPILE=\" /home/sathishpremabai/lineage/prebuilts/gcc/linux-x86/arm/arm-eabi-7.2/bi
n/arm-eabi-\"   headers_install ) && (echo \"/home/sathishpremabai/lineage/out/target/product/lux/obj/KERNEL_OBJ/.headers_install_deps: \\\\\" > /home/sathishpremabai/lineage/
out/target/product/lux/obj/KERNEL_OBJ/.headers_install_deps ) && (( cd kernel/motorola/msm8916;                 if grep -q '^version_h' 'Makefile'; then                      d
epdirs=\"arch/arm/include/uapi include/uapi\";          else                    depdirs=\"arch/arm/include/asm include\";               fi;             deps=\"Makefile \$(find
 \$depdirs -type f -name '*.h')\";              for f in \$deps; do                     echo \"  kernel/motorola/msm8916/\$f \\\\\" >> /home/sathishpremabai/lineage/out/target
/product/lux/obj/KERNEL_OBJ/.headers_install_deps;              done ;          echo \"\" >> /home/sathishpremabai/lineage/out/target/product/lux/obj/KERNEL_OBJ/.headers_insta
ll_deps ;               for f in \$deps; do                     echo \"kernel/motorola/msm8916/\$f:\" >> /home/sathishpremabai/lineage/out/target/product/lux/obj/KERNEL_OBJ/.h
eaders_install_deps;                    echo \"\" >> /home/sathishpremabai/lineage/out/target/product/lux/obj/KERNEL_OBJ/.headers_install_deps;                 done          )
 )"
make: Entering directory '/home/sathishpremabai/lineage/kernel/motorola/msm8916'
  CHK     include/generated/uapi/linux/version.h
  HOSTCC  scripts/basic/fixdep
mv: cannot stat 'scripts/basic/.fixdep.tmp': No such file or directory
scripts/Makefile.host:118: recipe for target 'scripts/basic/fixdep' failed
make[2]: *** [scripts/basic/fixdep] Error 1
/home/sathishpremabai/lineage/kernel/motorola/msm8916/Makefile:423: recipe for target 'scripts_basic' failed
make[1]: *** [scripts_basic] Error 2
Makefile:130: recipe for target 'sub-make' failed
make: *** [sub-make] Error 2
make: Leaving directory '/home/sathishpremabai/lineage/kernel/motorola/msm8916'



soln 1:https://forum.xda-developers.com/android/software-hacking/reference-how-to-compile-android-kernel-t3627297

edit 1:
soln1 doesnt work...still serching for soln 
********************************************************************************************************************************
