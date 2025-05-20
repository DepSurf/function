# Function: <code>kernfs_find_and_get</code>

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
In fs/sysfs/file.c (ffffffff8128c506)
Location: include/linux/kernfs.h:432
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_remove_file_self
```
```
In fs/sysfs/group.c (ffffffff8128d276)
Location: include/linux/kernfs.h:432
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81427877)
Location: include/linux/kernfs.h:432
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (ffffffff8169010c)
Location: include/linux/kernfs.h:432
Inline: True
Inline callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_run
```
```
In drivers/md/bitmap.c (ffffffff8169ee1c)
Location: include/linux/kernfs.h:432
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
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
In fs/sysfs/file.c (ffffffff812b9da4)
Location: include/linux/kernfs.h:440
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff812baafd)
Location: include/linux/kernfs.h:440
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81472b77)
Location: include/linux/kernfs.h:440
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (ffffffff816f8e70)
Location: include/linux/kernfs.h:440
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/bitmap.c (ffffffff817001e9)
Location: include/linux/kernfs.h:440
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
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
In fs/sysfs/file.c (ffffffff812cf4d4)
Location: include/linux/kernfs.h:452
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff812d022d)
Location: include/linux/kernfs.h:452
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81494d97)
Location: include/linux/kernfs.h:452
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (ffffffff8172a6e2)
Location: include/linux/kernfs.h:452
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/bitmap.c (ffffffff81731f1b)
Location: include/linux/kernfs.h:452
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
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
In fs/sysfs/file.c (ffffffff812dcc1b)
Location: include/linux/kernfs.h:462
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff812dd8ed)
Location: include/linux/kernfs.h:462
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149e797)
Location: include/linux/kernfs.h:462
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/region.c (ffffffff8163279f)
Location: include/linux/kernfs.h:462
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff817430b5)
Location: include/linux/kernfs.h:462
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/bitmap.c (ffffffff8174addd)
Location: include/linux/kernfs.h:462
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff817828c4)
Location: include/linux/kernfs.h:462
Inline: True
Inline callers:
  - drivers/leds/led-class.c:of_led_classdev_register
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
In fs/sysfs/file.c (ffffffff8130152b)
Location: include/linux/kernfs.h:486
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff8130221d)
Location: include/linux/kernfs.h:486
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814dd2d7)
Location: include/linux/kernfs.h:486
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/region.c (ffffffff8169b10f)
Location: include/linux/kernfs.h:486
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff817b51ee)
Location: include/linux/kernfs.h:486
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff817bd143)
Location: include/linux/kernfs.h:486
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff817f8c74)
Location: include/linux/kernfs.h:486
Inline: True
Inline callers:
  - drivers/leds/led-class.c:of_led_classdev_register
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
In fs/sysfs/file.c (ffffffff8132f26b)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff8133069b)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150c4a7)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/region.c (ffffffff816d743f)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff817fcdd1)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81805229)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff81842284)
Location: include/linux/kernfs.h:491
Inline: True
Inline callers:
  - drivers/leds/led-class.c:of_led_classdev_register
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
In fs/sysfs/file.c (ffffffff8134662b)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff81347a6b)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81521b07)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f551c)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff816f930f)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff81828ec5)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81831429)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff8186e1a4)
Location: include/linux/kernfs.h:492
Inline: True
Inline callers:
  - drivers/leds/led-class.c:of_led_classdev_register
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
In fs/sysfs/file.c (ffffffff8136e94b)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff8136fea3)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81550032)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172eda4)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81732d89)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff8186b4e6)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81873fca)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff818b241c)
Location: include/linux/kernfs.h:520
Inline: True
Inline callers:
  - drivers/leds/led-class.c:of_led_classdev_register
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
In fs/sysfs/file.c (ffffffff81386a76)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff81388228)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815714e2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817530df)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff817569a3)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff8189d2e2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff818a5dda)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff818e4d66)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff813d1947)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff813d2e39)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816159f2)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811c1a)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81815f93)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff8196d600)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81975d15)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff819b7e5b)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff813e36a7)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff813e4b99)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163c356)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81820e0a)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff8182513d)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff819744e9)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff8197ad05)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff819ba2f3)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff813ea2c7)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff813eb799)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8161fe96)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8180410a)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff818084cd)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff81958519)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff8195ef35)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff8199eaf1)
Location: include/linux/kernfs.h:546
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff8143c047)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff8143d529)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168f3b6)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e7da)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81892c9d)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff819fdcb8)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81a04875)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff81a4b794)
Location: include/linux/kernfs.h:551
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff814b751f)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff814b8f89)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817ae6f9)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7e4c)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff819dcf56)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff81b652ff)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81b6c534)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff81bb9e9c)
Location: include/linux/kernfs.h:535
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff8154e95f)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff81550699)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c7bc9)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52cdc)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81b58689)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff81d002ea)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81d08605)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff81d5f2e2)
Location: include/linux/kernfs.h:595
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff8158662f)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff81588389)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190ac69)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba618a)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81babbf9)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/usb/core/port.c (ffffffff81c9eecc)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/md/md.c (ffffffff81d6361b)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81d71795)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff81dca1d2)
Location: include/linux/kernfs.h:599
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff815bf18f)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff815c0f49)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:sysfs_remove_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81952965)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa40a)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81bfff39)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/usb/core/port.c (ffffffff81d53b1a)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/md/md.c (ffffffff81e1a3ec)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff81e28874)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff81e82cf6)
Location: include/linux/kernfs.h:600
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffff800010456684)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffff8000104584d0)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c8c04)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010953968)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffff800010957e4c)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffff800010af1a48)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffff800010afac60)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffff800010b49b5c)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
```
```
In drivers/of/kobj.c (ffff800010b6fe30)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
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
In fs/sysfs/file.c (c0618730)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (c061a158)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (c086633c)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/md/md.c (c0bd2fb8)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (c0bdb748)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (c0c32fc0)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
```
```
In drivers/of/kobj.c (c0c52750)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
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
In fs/sysfs/file.c (c00000000057051c)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (c000000000572ebc)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (c0000000008465c4)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00ab0)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (c000000000a061b8)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (c000000000bde040)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (c000000000be8d14)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1be18)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
```
```
In drivers/leds/led-class.c (c000000000c3e260)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
```
```
In drivers/of/kobj.c (c000000000c4afe0)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
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
In fs/sysfs/file.c (ffffffe0002e7e44)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffe0002e95f2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004ac332)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c31f2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffe0005c6d86)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffe0006e57a2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffe0006ec57e)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffe00071d11c)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
```
```
In drivers/of/kobj.c (ffffffe00072412a)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/of/kobj.c:safe_name
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
In fs/sysfs/file.c (ffffffff8137f056)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff81380808)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81566ca2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817077cf)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff8170b093)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff81843162)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff8184bc5a)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
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
In fs/sysfs/file.c (ffffffff8136fae6)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff81371298)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81557af2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/acpi/nfit/core.c (ffffffff815f8e10)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816db24f)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff816deb13)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/pmem.c (ffffffff816eb2a0)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
```
In drivers/md/md.c (ffffffff8180a7c2)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff8181327a)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
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
In fs/sysfs/file.c (ffffffff8137cb26)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff8137e2d8)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81565812)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8174659f)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff81749e63)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff81892792)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff8189b28a)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff818d9bc6)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
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
In fs/sysfs/file.c (ffffffff81390606)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/file.c:sysfs_file_change_owner
  - fs/sysfs/file.c:sysfs_remove_file_from_group
  - fs/sysfs/file.c:sysfs_remove_file_self
  - fs/sysfs/file.c:sysfs_break_active_protection
  - fs/sysfs/file.c:sysfs_chmod_file
  - fs/sysfs/file.c:sysfs_add_file_to_group
  - fs/sysfs/file.c:sysfs_notify
  - fs/sysfs/file.c:sysfs_notify
```
```
In fs/sysfs/group.c (ffffffff81391ed8)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:sysfs_group_change_owner
  - fs/sysfs/group.c:__compat_only_sysfs_link_entry_to_kobj
  - fs/sysfs/group.c:sysfs_remove_link_from_group
  - fs/sysfs/group.c:sysfs_add_link_to_group
  - fs/sysfs/group.c:sysfs_unmerge_group
  - fs/sysfs/group.c:sysfs_merge_group
  - fs/sysfs/group.c:internal_create_group
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157f732)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817619df)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
```
In drivers/nvdimm/region.c (ffffffff817652e3)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/md/md.c (ffffffff818ae36f)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:level_store
  - drivers/md/md.c:bind_rdev_to_array
```
```
In drivers/md/md-bitmap.c (ffffffff818b73ea)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_create
```
```
In drivers/leds/led-class.c (ffffffff818f66e6)
Location: include/linux/kernfs.h:521
Inline: True
Inline callers:
  - drivers/leds/led-class.c:led_classdev_register_ext
```
</details>
</li>
</ul>

## Differences
