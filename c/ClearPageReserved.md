# Function: <code>ClearPageReserved</code>

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
In arch/x86/mm/init_64.c (ffffffff8181bb85)
Location: include/linux/page-flags.h:222
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8110c458)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free_pages
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811951b1)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff811ef969)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff814c6c42)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff8151d720)
Location: include/linux/page-flags.h:222
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81895d9d)
Location: include/linux/page-flags.h:275
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81114f03)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff811a91f5)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8120ecb7)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815174d6)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff815704cd)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff818ca4bd)
Location: include/linux/page-flags.h:285
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111c61b)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff811b974d)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff81220ce7)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81543903)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff8159cb80)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81901a3c)
Location: include/linux/page-flags.h:285
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111e54b)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff811c17cd)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8122c5f7)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815577b2)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff815b0bb0)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff8198ba6c)
Location: include/linux/page-flags.h:286
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81129cab)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff811d5bed)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff81247dd7)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815bb8f0)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff81617756)
Location: include/linux/page-flags.h:286
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff819e8361)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81137bfb)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff811f702d)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8126b727)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815f3e4e)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff81651254)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81a23951)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8114341b)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff812093cd)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8127ffb7)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8160ecb2)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff8166f41f)
Location: include/linux/page-flags.h:304
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81a93c7b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8114e75b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff812728e9)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8129bfe5)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81642a75)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff816a4f7c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81acb55b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115a46b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff81281749)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812abd55)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8166501d)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff816c7cac)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81bc3a5d)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116b23b)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff812b3c33)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812e164c)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81713fc4)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
```
```
In drivers/char/agp/generic.c (ffffffff8177c9df)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81c3c988)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116797b)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff812bf6e7)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812ec59c)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81730f94)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
```
```
In drivers/char/agp/generic.c (ffffffff81795b2f)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81c2ee64)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116870b)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff812c4d67)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812c6e3c)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81714c98)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff817787ef)
Location: include/linux/page-flags.h:354
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81d4d565)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8118e43b)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff81309217)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff8136cb6c)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81791bbe)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/char/agp/generic.c (ffffffff817fe6b2)
Location: include/linux/page-flags.h:368
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81f1d26f)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811bd9eb)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff81371714)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff813eaf06)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff818ca840)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/char/agp/generic.c (ffffffff8193d315)
Location: include/linux/page-flags.h:518
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff820c53d5)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811ffb1f)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff813eee44)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff81473106)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a1b3ec)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/char/agp/generic.c (ffffffff81a9e185)
Location: include/linux/page-flags.h:497
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff82149435)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff812138b0)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff81422c14)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff814a7876)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a64580)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/char/agp/generic.c (ffffffff81ae9b23)
Location: include/linux/page-flags.h:490
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff8222bef5)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8122b80f)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff8144faf4)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff814d88a6)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81ab6de0)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/char/agp/generic.c (ffffffff81b3cfb3)
Location: include/linux/page-flags.h:492
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In kernel/kexec_core.c (ffff8000101c9aec)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffff800010319bd4)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffff80001034de10)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffff80001082ee04)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In kernel/kexec_core.c (c0410b04)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (c0534580)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_reserved_area
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
In arch/powerpc/kernel/crash_dump.c (c00000000004be1c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
```
```
In arch/powerpc/kernel/fadump.c (c00000000004c16c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
```
```
In arch/powerpc/mm/init_64.c (c000000000088e68)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
```
```
In arch/powerpc/platforms/powernv/opal-flash.c (c0000000000ca02c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-flash.c:image_data_write
```
```
In kernel/kexec_core.c (c000000000232580)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (c0000000003ecc64)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (c00000000042d33c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/char/agp/generic.c (c000000000955290)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
  - drivers/char/agp/generic.c:agp_generic_create_gatt_table
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021f6a4)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
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
In arch/x86/mm/init_64.c (ffffffff81a6a3cb)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81152a8b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff81279d99)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812a4335)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8162abb0)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff8168d6fc)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81a2688d)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81145d6b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff8126bc89)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff81295e05)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/char/agp/generic.c (ffffffff8166b0ec)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81ad67db)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115093b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff81277b39)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812a2145)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81658e5d)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff816bb96c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
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
In arch/x86/mm/init_64.c (ffffffff81ae2c9b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115d75b)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
  - kernel/kexec_core.c:kimage_free_pages
```
```
In mm/page_alloc.c (ffffffff81287729)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812b23d5)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8167346d)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/char/agp/generic.c (ffffffff816d5f3c)
Location: include/linux/page-flags.h:337
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_free_gatt_table
```
</details>
</li>
</ul>

## Differences
