# Function: <code>sysfs_notify_dirent</code>

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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81427826)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/md/md.c (ffffffff8168dd47)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:action_store
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:state_store
  - drivers/md/md.c:md_ioctl
```
```
In drivers/md/bitmap.c (ffffffff8169d14b)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81472b26)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/md/md.c (ffffffff816f2225)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
```
In drivers/md/bitmap.c (ffffffff816fe42b)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81494d46)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/md/md.c (ffffffff8172198a)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
```
```
In drivers/md/bitmap.c (ffffffff8173008b)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149e746)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff8162d87c)
Location: include/linux/sysfs.h:509
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81632545)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/md/md.c (ffffffff8173b867)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/bitmap.c (ffffffff81749b7b)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff817823ce)
Location: include/linux/sysfs.h:509
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff814dd286)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff8169603c)
Location: include/linux/sysfs.h:516
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff8169aeb5)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/md/md.c (ffffffff817aba17)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff817bbe5b)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff817f877e)
Location: include/linux/sysfs.h:516
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150c455)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff816d210c)
Location: include/linux/sysfs.h:528
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816d7285)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/md/md.c (ffffffff817f373a)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8180374b)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff81841d7e)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81521ab5)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff816f396c)
Location: include/linux/sysfs.h:528
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816f9155)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff817049b4)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff8181f71a)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8182ff3b)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff8186dc9e)
Location: include/linux/sysfs.h:528
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8154ffe5)
Location: include/linux/sysfs.h:536
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff8172cccd)
Location: include/linux/sysfs.h:536
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81732bf1)
Location: include/linux/sysfs.h:536
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff8173e7b4)
Location: include/linux/sysfs.h:536
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff818609ab)
Location: include/linux/sysfs.h:536
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81872672)
Location: include/linux/sysfs.h:536
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff818b1f4f)
Location: include/linux/sysfs.h:536
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81571495)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff81751480)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81756bc1)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81761df6)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff818925db)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff818a4472)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff818e4828)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff816159a5)
Location: include/linux/sysfs.h:592
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff8180f7e0)
Location: include/linux/sysfs.h:592
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff818161b1)
Location: include/linux/sysfs.h:592
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81822432)
Location: include/linux/sysfs.h:592
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff8196304b)
Location: include/linux/sysfs.h:592
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81973809)
Location: include/linux/sysfs.h:592
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff819b7948)
Location: include/linux/sysfs.h:592
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163c305)
Location: include/linux/sysfs.h:614
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff8181e720)
Location: include/linux/sysfs.h:614
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81825341)
Location: include/linux/sysfs.h:614
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81831142)
Location: include/linux/sysfs.h:614
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff8196a821)
Location: include/linux/sysfs.h:614
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81978709)
Location: include/linux/sysfs.h:614
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff819b9dc8)
Location: include/linux/sysfs.h:614
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8161fe45)
Location: include/linux/sysfs.h:616
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff81801c0e)
Location: include/linux/sysfs.h:616
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff818086d1)
Location: include/linux/sysfs.h:616
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81814202)
Location: include/linux/sysfs.h:616
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff8194e631)
Location: include/linux/sysfs.h:616
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8195d4e9)
Location: include/linux/sysfs.h:616
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff8199e5b8)
Location: include/linux/sysfs.h:616
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168f365)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff8188bf7e)
Location: include/linux/sysfs.h:622
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81892e91)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff8189e8a2)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff819f3a34)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81a02d49)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff81a4b238)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff817ae695)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff819d5816)
Location: include/linux/sysfs.h:622
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff819dcd89)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff819e8343)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff81b5d73b)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81b6a6aa)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff81bb9858)
Location: include/linux/sysfs.h:622
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c7b55)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff81b502d6)
Location: include/linux/sysfs.h:638
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81b58469)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81b63ea3)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff81cf762e)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81d064ea)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff81d5ebb8)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190abf5)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff81ba37a6)
Location: include/linux/sysfs.h:638
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81bab9d9)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81bb74a3)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/usb/core/hub.c (ffffffff81c79b96)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:update_port_device_state
```
```
In drivers/md/md.c (ffffffff81d5ef22)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81d6f56a)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff81dc99d8)
Location: include/linux/sysfs.h:638
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff819528f5)
Location: include/linux/sysfs.h:640
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff81bf7996)
Location: include/linux/sysfs.h:640
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81bffd19)
Location: include/linux/sysfs.h:640
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81c0baf3)
Location: include/linux/sysfs.h:640
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/usb/core/hub.c (ffffffff81d2e59b)
Location: include/linux/sysfs.h:640
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:update_port_device_state
```
```
In drivers/md/md.c (ffffffff81e16192)
Location: include/linux/sysfs.h:640
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_write_start
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81e2684a)
Location: include/linux/sysfs.h:640
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_cond_end_sync
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff81e824b8)
Location: include/linux/sysfs.h:640
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c8bb0)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffff800010951430)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (ffff8000109580c8)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffff800010961cd0)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffff800010ae8d4c)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffff800010af7e04)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffff800010b494f0)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (c08662f0)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/md/md.c (c0bcc4a0)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (c0bd76e0)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (c0c329fc)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (c00000000084654c)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (c0000000009fe528)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (c000000000a06508)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (c000000000a17b14)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (c000000000bcda70)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (c000000000be6d48)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (c000000000c3da3c)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004ac2e2)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1704)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffe0005c6ce2)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffe0005cf4e4)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffe0006dadd6)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffe0006ead3e)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffe00071cc28)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81566c55)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff81705b70)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff8170b2b1)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff817164e6)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff8183845b)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff8184a2f2)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff81557aa5)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/acpi/nfit/core.c (ffffffff815f611a)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_scrub
  - drivers/acpi/nfit/core.c:__acpi_nvdimm_notify
```
```
In drivers/nvdimm/bus.c (ffffffff816d95f0)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816ded31)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff816e9f66)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb982)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_do_bvec
```
```
In drivers/md/md.c (ffffffff817ffacb)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81811932)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff815657c5)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff81744940)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff8174a081)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff817552b6)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff81887a8b)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff81899922)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff818d9688)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
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
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157f6e5)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_irq
```
```
In drivers/nvdimm/bus.c (ffffffff8175fd80)
Location: include/linux/sysfs.h:591
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81765501)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_notify
```
```
In drivers/nvdimm/security.c (ffffffff81770726)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/md/md.c (ffffffff818a3dbb)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_start_sync
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_safemode_timeout
  - drivers/md/md.c:action_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:slot_store
  - drivers/md/md.c:state_store
  - drivers/md/md.c:add_bound_rdev
  - drivers/md/md.c:set_in_sync
```
```
In drivers/md/md-bitmap.c (ffffffff818b5462)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
```
```
In drivers/leds/led-class.c (ffffffff818f61a8)
Location: include/linux/sysfs.h:591
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_notify_brightness_hw_changed
```
</details>
</li>
</ul>

## Differences
