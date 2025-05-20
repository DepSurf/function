# Function: <code>sysfs_put</code>

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
In lib/kobject.c (ffffffff813eb878)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814277a0)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (ffffffff8168da66)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:md_free
```
```
In drivers/md/bitmap.c (ffffffff8169ed21)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_destroy
  - drivers/md/bitmap.c:bitmap_create
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
In lib/kobject.c (ffffffff81431c68)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81472a97)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (ffffffff816f0f6f)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/bitmap.c (ffffffff81700214)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_free
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
In lib/kobject.c (ffffffff8144ded8)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81494cb7)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (ffffffff8172281f)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/bitmap.c (ffffffff81731f46)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_free
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149e6b7)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/region.c (ffffffff816325f0)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff81739c4f)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/bitmap.c (ffffffff8174ae04)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff817825e2)
Location: include/linux/sysfs.h:526
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff818ee093)
Location: include/linux/sysfs.h:526
Inline: True
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff814dd1f7)
Location: include/linux/sysfs.h:533
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/region.c (ffffffff8169af60)
Location: include/linux/sysfs.h:533
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff817ac49f)
Location: include/linux/sysfs.h:533
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff817bd16a)
Location: include/linux/sysfs.h:533
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff817f8992)
Location: include/linux/sysfs.h:533
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff819743a3)
Location: include/linux/sysfs.h:533
Inline: True
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150c3c7)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/region.c (ffffffff816d7330)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff817f28bf)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff8180525a)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff81841fcf)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff819d08c3)
Location: include/linux/sysfs.h:545
Inline: True
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81521a27)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5135)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffff816f9200)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff8181e7bf)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff8183145a)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff8186deef)
Location: include/linux/sysfs.h:545
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff81a09ee3)
Location: include/linux/sysfs.h:545
Inline: True
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8154ff54)
Location: include/linux/sysfs.h:553
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172e9e5)
Location: include/linux/sysfs.h:553
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffff81732c8d)
Location: include/linux/sysfs.h:553
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff81860c8f)
Location: include/linux/sysfs.h:553
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff81873ffc)
Location: include/linux/sysfs.h:553
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff818b218d)
Location: include/linux/sysfs.h:553
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff81a7974d)
Location: include/linux/sysfs.h:553
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81571404)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81752ca5)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffff817568ad)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff818928bf)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff818a5e0c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff818e4afd)
Location: include/linux/sysfs.h:608
Inline: True
```
```
In lib/kobject.c (ffffffff81ab0aad)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In lib/kobject.c (ffffffff815eac9c)
Location: include/linux/sysfs.h:609
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81615ac8)
Location: include/linux/sysfs.h:609
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811c59)
Location: include/linux/sysfs.h:609
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81815e9d)
Location: include/linux/sysfs.h:609
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff81960a9f)
Location: include/linux/sysfs.h:609
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff81975d47)
Location: include/linux/sysfs.h:609
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff819b7c0d)
Location: include/linux/sysfs.h:609
Inline: True
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
In lib/kobject.c (ffffffff8160f5b3)
Location: include/linux/sysfs.h:631
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163c447)
Location: include/linux/sysfs.h:631
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81820e49)
Location: include/linux/sysfs.h:631
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff8182502d)
Location: include/linux/sysfs.h:631
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff8196739f)
Location: include/linux/sysfs.h:631
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff8197ad37)
Location: include/linux/sysfs.h:631
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff819ba08d)
Location: include/linux/sysfs.h:631
Inline: True
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
In lib/kobject.c (ffffffff815f2cf3)
Location: include/linux/sysfs.h:633
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8161ff8c)
Location: include/linux/sysfs.h:633
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804149)
Location: include/linux/sysfs.h:633
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff818083bd)
Location: include/linux/sysfs.h:633
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff8194b43f)
Location: include/linux/sysfs.h:633
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff8195ef67)
Location: include/linux/sysfs.h:633
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff8199e896)
Location: include/linux/sysfs.h:633
Inline: True
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
In lib/kobject.c (ffffffff8165fed3)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168f4ac)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e819)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81892b8d)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff819f05ff)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff81a048a7)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff81a4b54e)
Location: include/linux/sysfs.h:639
Inline: True
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
In lib/kobject.c (ffffffff817799b3)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817ae805)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7e8b)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff819dce3d)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff81b5896f)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c565)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff81bb9ac2)
Location: include/linux/sysfs.h:639
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c7cd5)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52d1b)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81b5853d)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff81cf2219)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff81d08637)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff81d5eea2)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff82022983)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190ad75)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba61d0)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81babaad)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/usb/core/port.c (ffffffff81c9f253)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/md/md.c (ffffffff81d5a109)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff81d717c7)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff81dc9d92)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff820a29f3)
Location: include/linux/sysfs.h:655
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81952a4f)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa450)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81bffded)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/usb/core/port.c (ffffffff81d53ea3)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/md/md.c (ffffffff81e112c9)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kobj_release
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff81e288a6)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff81e82962)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_unregister
```
```
In lib/kobject.c (ffffffff8217aa73)
Location: include/linux/sysfs.h:657
Inline: True
Inline callers:
  - lib/kobject.c:__kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c8ad8)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffff8000109533f8)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffff800010957d70)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffff800010ae40bc)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffff800010afac94)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffff800010b498c4)
Location: include/linux/sysfs.h:608
Inline: True
```
```
In drivers/of/kobj.c (ffff800010b6fe44)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
```
```
In lib/kobject.c (ffff800010d8ab1c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (c086624c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (c0bc69d0)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (c0bdb77c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (c0c32d40)
Location: include/linux/sysfs.h:608
Inline: True
```
```
In drivers/of/kobj.c (c0c52764)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
```
```
In lib/kobject.c (c0e852c8)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (c000000000846420)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00a2c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (c000000000a06090)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (c000000000bce148)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (c000000000be8d50)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (c000000000c3dfc0)
Location: include/linux/sysfs.h:608
Inline: True
```
```
In drivers/of/kobj.c (c000000000c4affc)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
```
```
In lib/kobject.c (c000000000ecbc3c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004ac228)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2daa)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffe0005c6c3e)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffe0006db13c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec5a8)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffe00071cef0)
Location: include/linux/sysfs.h:608
Inline: True
```
```
In drivers/of/kobj.c (ffffffe00072413c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
```
```
In lib/kobject.c (ffffffe0008b4076)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81566bc4)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81707395)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffff8170af9d)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff8183873f)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff8184bc8c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In lib/kobject.c (ffffffff81a4f8fd)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81557a14)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/acpi/nfit/core.c (ffffffff815f8e4a)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
  - drivers/acpi/nfit/core.c:shutdown_dimm_notify
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816dae15)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffff816dea1d)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/pmem.c (ffffffff816eacc6)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:nd_pmem_remove
```
```
In drivers/md/md.c (ffffffff817ffdaf)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff818132ac)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In lib/kobject.c (ffffffff81a0c9fd)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81565734)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81746165)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffff81749d6d)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff81887d6f)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff8189b2bc)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff818d995d)
Location: include/linux/sysfs.h:608
Inline: True
```
```
In lib/kobject.c (ffffffff81abbced)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157f654)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817615a5)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:shutdown_security_notify
```
```
In drivers/nvdimm/region.c (ffffffff817651ed)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/md/md.c (ffffffff818a409f)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md.c:md_free
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/md-bitmap.c (ffffffff818b741c)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_free
```
```
In drivers/leds/led-class.c (ffffffff818f647d)
Location: include/linux/sysfs.h:608
Inline: True
```
```
In lib/kobject.c (ffffffff81ac817d)
Location: include/linux/sysfs.h:608
Inline: True
Inline callers:
  - lib/kobject.c:kobject_del
```
</details>
</li>
</ul>

## Differences
