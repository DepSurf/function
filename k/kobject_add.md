# Function: <code>kobject_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813ec3a0)
Location: lib/kobject.c:394
Inline: False
Direct callers:
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff813ec3a0-ffffffff813ec46b: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81432680)
Location: lib/kobject.c:394
Inline: False
Direct callers:
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81432680-ffffffff81432750: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e8f0)
Location: lib/kobject.c:394
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff8144e8f0-ffffffff8144e9c0: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818eeb10)
Location: lib/kobject.c:394
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff818eeb10-ffffffff818eebdd: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974dd0)
Location: lib/kobject.c:394
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81974dd0-ffffffff81974e9d: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:410
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff819d1817-ffffffff819d184a: kobject_add.cold.15 (STB_LOCAL)
ffffffff819d1530-ffffffff819d15db: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:410
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81a0ad63-ffffffff81a0ad96: kobject_add.cold.14 (STB_LOCAL)
ffffffff81a0a8f0-ffffffff81a0a99b: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81a7a735-ffffffff81a7a768: kobject_add.cold (STB_LOCAL)
ffffffff81a7a2a0-ffffffff81a7a34c: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81ab1a95-ffffffff81ab1ac8: kobject_add.cold (STB_LOCAL)
ffffffff81ab1600-ffffffff81ab16ac: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
```
**Symbols:**

```
ffffffff815ebd98-ffffffff815ebdcb: kobject_add.cold (STB_LOCAL)
ffffffff815eb860-ffffffff815eb90c: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks
  - arch/x86/kernel/cpu/mce/amd.c:__threshold_add_blocks
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
```
**Symbols:**

```
ffffffff81bf4b1f-ffffffff81bf4b52: kobject_add.cold (STB_LOCAL)
ffffffff81610180-ffffffff8161022c: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81be6a28-ffffffff81be6a5b: kobject_add.cold (STB_LOCAL)
ffffffff815f38c0-ffffffff815f396c: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81cdf315-ffffffff81cdf348: kobject_add.cold (STB_LOCAL)
ffffffff81660a90-ffffffff81660b3c: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - lib/kobject.c:kobject_create_and_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
```
**Symbols:**

```
ffffffff81ea5ae9-ffffffff81ea5b1c: kobject_add.cold (STB_LOCAL)
ffffffff8177a5d0-ffffffff8177a6a3: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820236c0)
Location: lib/kobject.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff820236c0-ffffffff820237b8: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a3730)
Location: lib/kobject.c:403
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff820a3730-ffffffff820a382f: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217b7e0)
Location: lib/kobject.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/irq/irqdesc.c:alloc_descs
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
  - kernel/livepatch/core.c:klp_init_object
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff8217b7e0-ffffffff8217b8df: kobject_add (STB_GLOBAL)
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
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8b6b0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - arch/arm64/kernel/cpuinfo.c:cpuid_cpu_online
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffff800010d8b6b0-ffff800010d8b7a8: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85d98)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
c0e85d98-c0e85e60: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000eccfe0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-dump.c:process_dump
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
c000000000eccfe0-c000000000ecd0c8: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4a42)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/of/kobj.c:__of_attach_node_sysfs
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffe0008b4a42-ffffffe0008b4ad8: kobject_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81a508e5-ffffffff81a50918: kobject_add.cold (STB_LOCAL)
ffffffff81a50450-ffffffff81a504fc: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81a0d9e5-ffffffff81a0da18: kobject_add.cold (STB_LOCAL)
ffffffff81a0d550-ffffffff81a0d5fc: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81abccd5-ffffffff81abcd08: kobject_add.cold (STB_LOCAL)
ffffffff81abc840-ffffffff81abc8ec: kobject_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kobject_add(struct kobject *kobj, struct kobject *parent, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:426
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:irq_sysfs_add
  - block/elevator.c:elv_register_queue
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - block/blk-mq-sysfs.c:blk_mq_register_hctx
  - drivers/base/core.c:device_add
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/firmware/memmap.c:add_sysfs_fw_map_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create_and_add
```
**Symbols:**

```
ffffffff81ac9158-ffffffff81ac918b: kobject_add.cold (STB_LOCAL)
ffffffff81ac8cc0-ffffffff81ac8d6c: kobject_add (STB_GLOBAL)
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
