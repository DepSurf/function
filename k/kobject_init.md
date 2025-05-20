# Function: <code>kobject_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb600)
Location: lib/kobject.c:325
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff813eb600-ffffffff813eb682: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431960)
Location: lib/kobject.c:325
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:blk_mq_register_disk
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81431960-ffffffff814319e2: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144dbd0)
Location: lib/kobject.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/padata.c:padata_alloc
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff8144dbd0-ffffffff8144dc52: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818eded0)
Location: lib/kobject.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/padata.c:padata_alloc_possible
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff818eded0-ffffffff818edf52: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819740b0)
Location: lib/kobject.c:325
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/padata.c:padata_alloc_possible
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff819740b0-ffffffff81974132: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:341
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/padata.c:padata_alloc_possible
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff819d1776-ffffffff819d17b8: kobject_init.cold.12 (STB_LOCAL)
ffffffff819d0600-ffffffff819d0652: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:341
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/padata.c:padata_alloc_possible
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff81a0acd6-ffffffff81a0ad18: kobject_init.cold.12 (STB_LOCAL)
ffffffff81a09b60-ffffffff81a09bb2: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff81a7a6a7-ffffffff81a7a6e9: kobject_init.cold (STB_LOCAL)
ffffffff81a793f0-ffffffff81a7944c: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff81ab1a07-ffffffff81ab1a49: kobject_init.cold (STB_LOCAL)
ffffffff81ab0750-ffffffff81ab07ac: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff815eb93e)
Location: lib/kobject.c:349
Inline: True
Inline callers:
  - lib/kobject.c:kobject_create_and_add
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_object_nops
  - kernel/livepatch/core.c:klp_add_object_nops
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/memmap.c:firmware_map_add_entry
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
```
**Symbols:**

```
ffffffff815ebd0a-ffffffff815ebd4c: kobject_init.cold (STB_LOCAL)
ffffffff815ea950-ffffffff815ea9ac: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff8161025e)
Location: lib/kobject.c:349
Inline: True
Inline callers:
  - lib/kobject.c:kobject_create_and_add
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_object_nops
  - kernel/livepatch/core.c:klp_add_object_nops
  - kernel/padata.c:padata_alloc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/memmap.c:firmware_map_add_entry
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
```
**Symbols:**

```
ffffffff81bf4a91-ffffffff81bf4ad3: kobject_init.cold (STB_LOCAL)
ffffffff8160f270-ffffffff8160f2cc: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff815f399e)
Location: lib/kobject.c:349
Inline: True
Inline callers:
  - lib/kobject.c:kobject_create_and_add
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/padata.c:padata_alloc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/memmap.c:firmware_map_add_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81be699a-ffffffff81be69dc: kobject_init.cold (STB_LOCAL)
ffffffff815f29b0-ffffffff815f2a0c: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff81660b6e)
Location: lib/kobject.c:349
Inline: True
Inline callers:
  - lib/kobject.c:kobject_create_and_add
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/padata.c:padata_alloc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/memmap.c:firmware_map_add_entry
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
**Symbols:**

```
ffffffff81cdf287-ffffffff81cdf2c9: kobject_init.cold (STB_LOCAL)
ffffffff8165fb90-ffffffff8165fbec: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, const struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/kobject.c (ffffffff8177a6e1)
Location: lib/kobject.c:317
Inline: True
Inline callers:
  - lib/kobject.c:kobject_create_and_add
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/padata.c:padata_alloc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - lib/kobject.c:kobject_init_and_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/memmap.c:firmware_map_add_entry
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
```
**Symbols:**

```
ffffffff81ea5a5c-ffffffff81ea5a9e: kobject_init.cold (STB_LOCAL)
ffffffff81779690-ffffffff817796ee: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, const struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820226a0)
Location: lib/kobject.c:325
Inline: True
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/padata.c:padata_alloc
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_import_device
  - drivers/firmware/memmap.c:firmware_map_add_early
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff820226a0-ffffffff8202273d: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, const struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2700)
Location: lib/kobject.c:326
Inline: True
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/padata.c:padata_alloc
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_import_device
  - drivers/firmware/memmap.c:firmware_map_add_early
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff820a2700-ffffffff820a27af: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, const struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217a780)
Location: lib/kobject.c:333
Inline: True
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/padata.c:padata_alloc
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-sysfs.c:blk_register_queue
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_import_device
  - drivers/firmware/memmap.c:firmware_map_add_early
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
  - lib/kobject.c:kobject_create_and_add
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff8217a780-ffffffff8217a82f: kobject_init (STB_GLOBAL)
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
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8a4b8)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - arch/arm64/kernel/cpuinfo.c:cpuinfo_regs_init
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffff800010d8a4b8-ffff800010d8a554: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e84e1c)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
c0e84e1c-c0e84eb8: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecb5a0)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - arch/powerpc/kernel/secvar-sysfs.c:secvar_sysfs_init
  - arch/powerpc/platforms/powernv/opal-elog.c:elog_event
  - arch/powerpc/platforms/powernv/opal-dump.c:process_dump
  - arch/powerpc/platforms/pseries/reconfig.c:ofdt_write
  - arch/powerpc/platforms/pseries/dlpar.c:dlpar_parse_cc_node
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
c000000000ecb5a0-c000000000ecb68c: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b3b1c)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/of/dynamic.c:__of_node_dup
  - drivers/of/fdt.c:unflatten_dt_nodes
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffe0008b3b1c-ffffffe0008b3bac: kobject_init (STB_GLOBAL)
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
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff81a50857-ffffffff81a50899: kobject_init.cold (STB_LOCAL)
ffffffff81a4f5a0-ffffffff81a4f5fc: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff81a0d957-ffffffff81a0d999: kobject_init.cold (STB_LOCAL)
ffffffff81a0c6a0-ffffffff81a0c6fc: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff81abcc47-ffffffff81abcc89: kobject_init.cold (STB_LOCAL)
ffffffff81abb990-ffffffff81abb9ec: kobject_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void kobject_init(struct kobject *kobj, struct kobj_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/kobject.c (0)
Location: lib/kobject.c:349
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
  - mm/slub.c:sysfs_slab_add
  - fs/char_dev.c:cdev_init
  - fs/char_dev.c:cdev_alloc
  - block/elevator.c:elevator_alloc
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_hctx_kobj_init
  - drivers/base/core.c:device_initialize
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:mddev_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - lib/kobject.c:kobject_create
  - lib/kobject.c:kobject_init_and_add
```
**Symbols:**

```
ffffffff81ac90ca-ffffffff81ac910c: kobject_init.cold (STB_LOCAL)
ffffffff81ac7eb0-ffffffff81ac7f0c: kobject_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobj_type *ktype</code> ➡️ <code>const struct kobj_type *ktype</code>
</li>
</ul>
</details>
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
