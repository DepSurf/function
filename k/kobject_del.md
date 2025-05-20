# Function: <code>kobject_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb860)
Location: lib/kobject.c:569
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-mq-sysfs.c:blk_mq_unregister_disk
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kobject_release
  - lib/kobject.c:kset_unregister
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_delayed_delete
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff813eb860-ffffffff813eb8a3: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431c50)
Location: lib/kobject.c:569
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - arch/x86/kernel/cpu/mcheck/mce_amd.c:amd_64_threshold_cpu_callback
  - mm/slub.c:sysfs_slab_remove
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_unregister_disk
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_release
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff81431c50-ffffffff81431c93: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144dec0)
Location: lib/kobject.c:569
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_remove
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kobject_release
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
```
**Symbols:**

```
ffffffff8144dec0-ffffffff8144df03: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff818ee13f)
Location: lib/kobject.c:569
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffff818ee080-ffffffff818ee0bd: kobject_del.part.5 (STB_LOCAL)
ffffffff818ee0c0-ffffffff818ee0d2: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff81974432)
Location: lib/kobject.c:569
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_remove_workfn
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81974390-ffffffff819743cd: kobject_del.part.5 (STB_LOCAL)
ffffffff819743d0-ffffffff819743e2: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff819d095a)
Location: lib/kobject.c:584
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff819d08b0-ffffffff819d08ed: kobject_del.part.8 (STB_LOCAL)
ffffffff819d08f0-ffffffff819d0901: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff81a09f7a)
Location: lib/kobject.c:584
Inline: True
Inline callers:
  - lib/kobject.c:kobject_release
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a09ed0-ffffffff81a09f0d: kobject_del.part.8 (STB_LOCAL)
ffffffff81a09f10-ffffffff81a09f21: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79720)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a79720-ffffffff81a79778: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0a80)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81ab0a80-ffffffff81ab0ad8: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eaef5)
Location: lib/kobject.c:638
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff815eaf30-ffffffff815eaf53: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f815)
Location: lib/kobject.c:635
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff8160f850-ffffffff8160f873: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2f55)
Location: lib/kobject.c:635
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff815f2f90-ffffffff815f2fb3: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81660125)
Location: lib/kobject.c:635
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elevator_switch_mq
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81660160-ffffffff81660183: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779c65)
Location: lib/kobject.c:603
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff81779cb0-ffffffff81779cde: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022c75)
Location: lib/kobject.c:611
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/class.c:__class_register
  - drivers/md/md.c:rdev_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff82022cd0-ffffffff82022cfe: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2ce5)
Location: lib/kobject.c:612
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/class.c:class_register
  - drivers/md/md.c:mddev_unlock
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff820a2d40-ffffffff820a2d6e: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217ad65)
Location: lib/kobject.c:619
Inline: True
Inline callers:
  - lib/kobject.c:kset_unregister
  - lib/kobject.c:kset_unregister
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/elevator.c:elv_unregister_queue
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_unregister_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - block/blk-ia-ranges.c:disk_register_independent_access_ranges
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/class.c:class_register
  - drivers/md/md.c:mddev_unlock
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
```
**Symbols:**

```
ffffffff8217adc0-ffffffff8217adee: kobject_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8aaf0)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/arm64/kernel/cpuinfo.c:cpuid_cpu_offline
  - arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffff800010d8aaf0-ffff800010d8ab54: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85294)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
c0e85294-c0e852f8: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecbbf0)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/powerpc/kernel/cacheinfo.c:cacheinfo_cpu_offline
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
c000000000ecbbf0-c000000000ecbc84: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b404a)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/of/kobj.c:__of_detach_node_sysfs
  - lib/kobject.c:kobject_put
```
**Symbols:**

```
ffffffe0008b404a-ffffffe0008b40b0: kobject_del (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4f8d0)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a4f8d0-ffffffff81a4f928: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0c9d0)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81a0c9d0-ffffffff81a0ca28: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbcc0)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81abbcc0-ffffffff81abbd18: kobject_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kobject_del(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8150)
Location: lib/kobject.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - arch/x86/kernel/cpu/mce/amd.c:mce_threshold_remove_device
  - kernel/irq/irqdesc.c:free_desc
  - mm/slub.c:sysfs_slab_unlink
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:sysfs_slab_add
  - fs/ext4/sysfs.c:ext4_unregister_sysfs
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-integrity.c:blk_integrity_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
  - drivers/md/md.c:mddev_delayed_delete
  - drivers/md/md.c:md_delayed_delete
  - drivers/firmware/dmi_scan.c:dmi_init
  - drivers/firmware/efi/rci2-table.c:efi_rci2_sysfs_init
  - lib/kobject.c:kobject_release
```
**Symbols:**

```
ffffffff81ac8150-ffffffff81ac81a8: kobject_del (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
