# Function: <code>SetPageReserved</code>

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
In kernel/kexec_core.c (ffffffff8110c4b3)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff8181ce6e)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory_hotplug.c (ffffffff81819823)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
```
```
In drivers/char/agp/generic.c (ffffffff8151d53b)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff81113d33)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811acc4b)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff81893417)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
```
```
In drivers/char/agp/generic.c (ffffffff815702a4)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8111b443)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811bd206)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff818c7c68)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
```
```
In drivers/char/agp/generic.c (ffffffff8159c957)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8111d303)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811c5463)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff818ff249)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
```
```
In drivers/char/agp/generic.c (ffffffff815b09b4)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff81128a2e)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811da22e)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In mm/memory_hotplug.c (ffffffff8198933a)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
```
```
In drivers/char/agp/generic.c (ffffffff81617554)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff81136aae)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff811faaa2)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:reserve_bootmem_region
```
```
In drivers/char/agp/generic.c (ffffffff8165105d)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8114210e)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff8120d222)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (ffffffff8166f21d)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8114d4d4)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81273653)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (ffffffff816a4d81)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff811591bf)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff812824c3)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (ffffffff816c7ab1)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff81169fe8)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff8177cb90)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff81166728)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff81795ce0)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff811674c8)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff8177899f)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8118d045)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff817fe86e)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff811bc297)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff8193d09b)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff811fe4c7)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff81a9deeb)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff81213798)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff81ae988a)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8122b6c8)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In drivers/char/agp/generic.c (ffffffff81b3cd1a)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffff8000101c87c8)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c040f748)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
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
In arch/powerpc/kernel/fadump.c (c00000000004d4e0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_setup_cpu_notes_buf
```
```
In arch/powerpc/platforms/powernv/opal-flash.c (c0000000000ca14c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
```
```
In kernel/kexec_core.c (c000000000230eb0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (c0000000003ee0e0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (c000000000956830)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/kexec_core.c (ffffffff811517df)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff8127ab13)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (ffffffff8168d501)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff81144abf)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff8126c9f3)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (ffffffff8166aef1)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8114f68f)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff812788b3)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (ffffffff816bb771)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
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
In kernel/kexec_core.c (ffffffff8115c4af)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In mm/page_alloc.c (ffffffff812884a3)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In drivers/char/agp/generic.c (ffffffff816d5d41)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
</details>
</li>
</ul>

## Differences
