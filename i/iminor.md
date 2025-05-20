# Function: <code>iminor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In kernel/power/swap.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In mm/page_io.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In security/device_cgroup.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In block/bsg.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8146e088)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/char/mem.c (ffffffff81510ef5)
Location: include/linux/fs.h:771
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/char/agp/frontend.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/linux/fs.h:771
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/linux/fs.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d106e)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In kernel/power/swap.c (ffffffff810d75ff)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff811efb0b)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In security/device_cgroup.c (ffffffff813d140a)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_inode_permission
```
```
In block/bsg.c (ffffffff8141bfc8)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814bc3d8)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81530ef0)
Location: include/linux/fs.h:833
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81540fec)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/char/mem.c (ffffffff81563475)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81568875)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff8156e795)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff815ec6b5)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff8161d49d)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff816773d0)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff816df5be)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d7ade)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In kernel/power/swap.c (ffffffff810de17b)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812004ab)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In security/device_cgroup.c (ffffffff813e8b3a)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_inode_permission
```
```
In block/bsg.c (ffffffff81437108)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814de3d8)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff8155d640)
Location: include/linux/fs.h:786
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8156d62c)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/char/mem.c (ffffffff8158fbe5)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81594fd5)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff8159ae55)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff81619495)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff8164e09d)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff816a50b0)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff8170f99e)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d6b1e)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In kernel/power/swap.c (ffffffff810dd28a)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8120b103)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In security/device_cgroup.c (ffffffff813f4ed6)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - security/device_cgroup.c:__devcgroup_inode_permission
```
```
In block/bsg.c (ffffffff814444c8)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff814e99c8)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81572530)
Location: include/linux/fs.h:805
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81581b9c)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/char/mem.c (ffffffff815a3cb5)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff815a9095)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff815aeeb5)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff8162d2d5)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff816629cd)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff816ba440)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff817254ee)
Location: include/linux/fs.h:805
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810deaae)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff8127f069)
Location: include/linux/fs.h:809
Inline: True
```
```
In fs/block_dev.c (ffffffff812b4e79)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff814713e8)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8151e518)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff815d68b0)
Location: include/linux/fs.h:809
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff815e66bc)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/char/mem.c (ffffffff8160a585)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff8160f995)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff81615a25)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff81695a75)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff816cc01d)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff81725dd0)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff8179697e)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810e70e5)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812a7a95)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812dd023)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff814a5417)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815540cb)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff8161306d)
Location: include/linux/fs.h:816
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8161f945)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/char/mem.c (ffffffff81643ec5)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff816497c5)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff8164f7a5)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff816d1b25)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff8170895f)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff81764b90)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9375)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c0ce)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In kernel/power/qos.c (ffffffff810f26e5)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812bcb35)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff812f2483)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff814bfe87)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8156b8ab)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff8163010d)
Location: include/linux/fs.h:864
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8163d55d)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffffffff81662195)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81667ac5)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff8166d595)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff816f31b5)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff8172ae4f)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff81789210)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81800515)
Location: include/linux/fs.h:864
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f41e)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In kernel/power/qos.c (ffffffff810fabb5)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812d9642)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff81313eab)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff814ee5d7)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8159c1cb)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81664039)
Location: include/linux/fs.h:879
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff816719cd)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffffffff81697d45)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff8169d345)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff816a3145)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff8172c715)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff81766570)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff817c7690)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81841745)
Location: include/linux/fs.h:879
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fcfe)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In kernel/power/qos.c (ffffffff81106a55)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812eb152)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8132768b)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff81507a37)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815bd7cb)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff816866a9)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81693e9d)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffffffff816ba8c5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff816c00e5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff816c5ed5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff81750955)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff8178a560)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/vfio/vfio.c (ffffffff817d13f5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff817f81b0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff818730c5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106584e)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff81323741)
Location: include/linux/fs.h:911
Inline: True
```
```
In fs/block_dev.c (ffffffff8136098b)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff81568d72)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81667955)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81738795)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81746125)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
```
In drivers/char/mem.c (ffffffff8176ed35)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81773ff5)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff8177aa45)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff8180f1a5)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81829ae5)
Location: include/linux/fs.h:911
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8184eed5)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/vfio/vfio.c (ffffffff8189d545)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff818c8270)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff819472b5)
Location: include/linux/fs.h:911
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81063afe)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff8132ece1)
Location: include/linux/fs.h:874
Inline: True
```
```
In block/bsg.c (ffffffff815836a2)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81688525)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81c0765d)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81761ae5)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
```
In drivers/char/mem.c (ffffffff81789615)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff8178ed75)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffff8181e0e5)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dma-buf/dma-heap.c (ffffffff8183a4b6)
Location: include/linux/fs.h:874
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8185f855)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/vfio/vfio.c (ffffffff818ac175)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff818d3420)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194d0c5)
Location: include/linux/fs.h:874
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106419e)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff81334ab2)
Location: include/linux/fs.h:875
Inline: True
```
```
In block/bsg.c (ffffffff8158a4b2)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8166b295)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81bf91c9)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff817457b5)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
```
In drivers/char/mem.c (ffffffff8176cef5)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81771b65)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffff81801435)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dax/super.c (ffffffff81814c15)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_free_inode
```
```
In drivers/dma-buf/dma-heap.c (ffffffff8181d6d6)
Location: include/linux/fs.h:875
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81842855)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
```
```
In drivers/vfio/vfio.c (ffffffff8188f2a5)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff818b69b0)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81930c35)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106e18e)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff813823f2)
Location: include/linux/fs.h:920
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff816de585)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81cf8966)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff817c6725)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
```
In drivers/char/mem.c (ffffffff817f2635)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff817f7905)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffff8188b885)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dax/super.c (ffffffff8189f3d5)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_free_inode
```
```
In drivers/dma-buf/dma-heap.c (ffffffff818a7b06)
Location: include/linux/fs.h:920
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff818cf955)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
```
```
In drivers/vfio/vfio.c (ffffffff81922875)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff8194c2c4)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d3f05)
Location: include/linux/fs.h:920
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107b9ce)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff81401902)
Location: include/linux/fs.h:875
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81808bb5)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81ec0a11)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81903685)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
```
In drivers/char/mem.c (ffffffff81932ef5)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81936095)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffff819d4c75)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dax/super.c (ffffffff819e91e1)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_free_inode
```
```
In drivers/dma-buf/dma-heap.c (ffffffff819f1865)
Location: include/linux/fs.h:875
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81a1e1a5)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
```
```
In drivers/usb/core/file.c (ffffffff81aa4d94)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b36ac5)
Location: include/linux/fs.h:875
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108cdce)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff8148ba02)
Location: include/linux/fs.h:890
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff81937535)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81a4b6ce)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81a5d6e5)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
```
In drivers/char/mem.c (ffffffff81a91be5)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81a95b95)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffff81b4f585)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dax/super.c (ffffffff81b658c1)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_free_inode
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81b6f505)
Location: include/linux/fs.h:890
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81b9f4e5)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
```
```
In drivers/usb/core/file.c (ffffffff81c2b724)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccbb35)
Location: include/linux/fs.h:890
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108fbce)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff814bfa57)
Location: include/linux/fs.h:905
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff8197b5d5)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81a957d6)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81aa7d45)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
```
In drivers/char/mem.c (ffffffff81add455)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81ae1395)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffff81ba2b45)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dax/super.c (ffffffff81bb8ee1)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_free_inode
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81bc2dc5)
Location: include/linux/fs.h:905
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81bf5c05)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_port_fops_open
```
```
In drivers/usb/core/file.c (ffffffff81c926c4)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d338e5)
Location: include/linux/fs.h:905
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81096f5e)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In fs/namei.c (ffffffff814f1f47)
Location: include/linux/fs.h:938
Inline: True
```
```
In drivers/video/fbdev/core/fb_chrdev.c (ffffffff819ca165)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_chrdev.c:fb_open
  - drivers/video/fbdev/core/fb_chrdev.c:fb_mmap
  - drivers/video/fbdev/core/fb_chrdev.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:fb_ioctl
  - drivers/video/fbdev/core/fb_chrdev.c:fb_write
  - drivers/video/fbdev/core/fb_chrdev.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81ae8236)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81afa7d5)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
```
In drivers/char/mem.c (ffffffff81b30865)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81b34785)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffff81bf6d05)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/dax/super.c (ffffffff81c0d541)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_free_inode
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81c17555)
Location: include/linux/fs.h:938
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff81c4b5a5)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c6e8)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_stub_open
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97ba5)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_open
```
```
In drivers/accel/drm_accel.c (ffffffff81cbcd25)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/accel/drm_accel.c:accel_stub_open
  - drivers/accel/drm_accel.c:accel_open
```
```
In drivers/usb/core/file.c (ffffffff81d47324)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81de99f5)
Location: include/linux/fs.h:938
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016d5bc)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffff80001039482c)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffff8000103e25ec)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffff800010609964)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffff800010743a40)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffff80001084f060)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffff8000108682d4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffff8000108aabdc)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffff8000108b2108)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffff80001095085c)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffff8000109920a4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffff800010a28ed4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab6f40)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b8614)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (c0579d18)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c05ba7e0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (c07b52d4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (c08c8298)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (c095b260)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (c096cb44)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
```
```
In drivers/char/mem.c (c09a6f78)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (c09aceec)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/scsi/sg.c (c0a635d8)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/mtd/mtdchar.c (c0a94ee4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/mtd/mtdchar.c:mtdchar_open
```
```
In drivers/usb/core/file.c (c0afeea4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (c0b97094)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
```
In sound/sound_core.c (c0c8241c)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - sound/sound_core.c:soundcore_open
```
```
In sound/core/sound.c (c0c83180)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - sound/core/sound.c:snd_open
```
```
In sound/core/control.c (c0c859ec)
Location: include/linux/fs.h:893
Inline: True
```
```
In sound/core/pcm_native.c (c0c95f50)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_common_ioctl
```
```
In sound/core/compress_offload.c (c0c9d354)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c4d40)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (c00000000048b24c)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (c0000000004e82d4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (c0000000007a6980)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a5598)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (c0000000008ee4ec)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (c000000000906ea0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
```
```
In drivers/char/mem.c (c0000000009422d0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (c00000000094b038)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (c000000000952ef0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (c0000000009fd248)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (c000000000a54178)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/vfio/vfio.c (c000000000aaeb0c)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (c000000000ae5134)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (c000000000b9aca4)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010ce0a)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffe0002632e0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffe000298b72)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffe0004436be)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f4d16)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffe00052d6a4)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffe00053ca4e)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_open
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_vc
```
```
In drivers/char/mem.c (ffffffe00055fb7e)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffe0005647e2)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/nvdimm/bus.c (ffffffe0005c09d0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffe0005f4f62)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffe00064a904)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bcfc6)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f87e)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In kernel/power/qos.c (ffffffff810ffd65)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812e3732)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131fc6b)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff81500017)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b191b)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff8164c129)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff8165991d)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffffffff81680325)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff81685b35)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff8168b925)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff81705045)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff8173ec50)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/usb/core/file.c (ffffffff817b0590)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fbae)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In kernel/power/qos.c (ffffffff810eff55)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812d4372)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131080b)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff814f0527)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815a0aab)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff8162c579)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81639c9d)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffffffff8165dff5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff816637d5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff81669325)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff816d8ac5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff817208f0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/vfio/vfio.c (ffffffff8177b4a5)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff817a1f90)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fcae)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In kernel/power/qos.c (ffffffff810fcf25)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812e1542)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8131d73b)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff814fc0a7)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815b1eab)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff8167a4e9)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81687cdd)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffffffff816ae705)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff816b3f25)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff816b9b95)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff81743e15)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff8177f3e0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/vfio/vfio.c (ffffffff817c6275)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff817ed030)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81867255)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106120e)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_dev_open
```
```
In kernel/power/qos.c (ffffffff81108175)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_power_open
```
```
In fs/namei.c (ffffffff812f0b22)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/namei.c:inode_permission
```
```
In fs/block_dev.c (ffffffff8132f43b)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
```
```
In block/bsg.c (ffffffff81515157)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_open
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff815cb91b)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_open
  - drivers/video/fbdev/core/fbmem.c:fb_mmap
  - drivers/video/fbdev/core/fbmem.c:fb_compat_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_ioctl
  - drivers/video/fbdev/core/fbmem.c:fb_write
  - drivers/video/fbdev/core/fbmem.c:fb_read
```
```
In drivers/tty/tty_io.c (ffffffff81694b91)
Location: include/linux/fs.h:893
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (ffffffff816a22cd)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/tty/vt/vc_screen.c:vcs_read
```
```
In drivers/char/mem.c (ffffffff816c8b65)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/mem.c:memory_open
```
```
In drivers/char/misc.c (ffffffff816ce485)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/misc.c:misc_open
```
```
In drivers/char/agp/frontend.c (ffffffff816d4165)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_open
```
```
In drivers/nvdimm/bus.c (ffffffff8175f265)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_open
```
```
In drivers/scsi/sg.c (ffffffff817991e0)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/vfio/vfio.c (ffffffff817e0515)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_open
```
```
In drivers/usb/core/file.c (ffffffff81807270)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_open
  - drivers/usb/core/file.c:usb_open
```
```
In drivers/i2c/i2c-dev.c (ffffffff81882885)
Location: include/linux/fs.h:893
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_open
  - drivers/i2c/i2c-dev.c:i2cdev_write
  - drivers/i2c/i2c-dev.c:i2cdev_read
```
</details>
</li>
</ul>

## Differences
