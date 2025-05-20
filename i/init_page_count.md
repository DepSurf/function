# Function: <code>init_page_count</code>

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
In arch/x86/mm/init_64.c (ffffffff8181bb8f)
Location: include/linux/mm.h:511
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8110d5fd)
Location: include/linux/mm.h:511
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811951bd)
Location: include/linux/mm.h:511
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff811ef970)
Location: include/linux/mm.h:511
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff814c6c4a)
Location: include/linux/mm.h:511
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81895da7)
Location: include/linux/page_ref.h:85
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81114f0d)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811a9201)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff8120ecbe)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815174de)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff818ca4c7)
Location: include/linux/page_ref.h:85
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111c625)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811b9757)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff81220cee)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8154390e)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81901a46)
Location: include/linux/page_ref.h:85
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111e555)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811c17d7)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff8122c5fe)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815577bc)
Location: include/linux/page_ref.h:85
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff8198ba76)
Location: include/linux/page_ref.h:86
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81129cb5)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811d5bf7)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff81247dde)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815bb8fa)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff819e8366)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81137c00)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811f7033)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff8126b72c)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815f3e53)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81a23956)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81143420)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812093d3)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8127ffbc)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8160ecb8)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81a93c82)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8114e762)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812728ef)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff8129bfee)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81642a7b)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81acb562)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115a472)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8128174f)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff812abd5e)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81665023)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81bc3a64)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116b242)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812b3c39)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff812e1651)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81713fcb)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
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
In arch/x86/mm/init_64.c (ffffffff81c3c98d)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81167982)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812bf6ed)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812ec5a1)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81730f9b)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:increase_reservation
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
In arch/x86/mm/init_64.c (ffffffff81c2ee69)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81168712)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812c4d6d)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812c6e41)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81714c9e)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81d4d56a)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8118e442)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8130921d)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff8136cb71)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81791bc4)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff81f1d274)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811bd9f0)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81371719)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff813eaf0b)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff818ca846)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff820c53da)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811ffb24)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
```
```
In mm/page_alloc.c (ffffffff813eee49)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
```
```
In mm/bootmem_info.c (ffffffff8147310b)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a1b3f2)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff8214943a)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff812138b5)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
```
```
In mm/mm_init.c (ffffffff8214bfbc)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/page_alloc.c (ffffffff81422c19)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff814a787b)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a64587)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In arch/x86/mm/init_64.c (ffffffff8222befa)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8122b814)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
```
```
In mm/mm_init.c (ffffffff8222eb52)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/page_alloc.c (ffffffff8144faf9)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff814d88ab)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81ab6de7)
Location: include/linux/page_ref.h:113
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
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
In kernel/kexec_core.c (ffff8000101c9afc)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffff800010319be4)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffff80001034de20)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffff80001082ee14)
Location: include/linux/page_ref.h:86
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
In kernel/kexec_core.c (c0410b0c)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (c0534590)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_highmem_page
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
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
In arch/powerpc/kernel/crash_dump.c (c00000000004be2c)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
```
```
In arch/powerpc/kernel/fadump.c (c00000000004c17c)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
```
```
In arch/powerpc/mm/init_64.c (c000000000088e78)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
```
```
In kernel/kexec_core.c (c000000000232590)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (c0000000003ecc74)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (c00000000042d350)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
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
In mm/page_alloc.c (ffffffe00021f6ae)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone
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
In arch/x86/mm/init_64.c (ffffffff81a6a3d2)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81152a92)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81279d9f)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff812a433e)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8162abb6)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81a26894)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81145d72)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8126bc8f)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff81295e0e)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
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
In arch/x86/mm/init_64.c (ffffffff81ad67e2)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81150942)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81277b3f)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff812a214e)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81658e63)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
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
In arch/x86/mm/init_64.c (ffffffff81ae2ca2)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115d762)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8128772f)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/memory_hotplug.c (ffffffff812b23de)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__online_page_free
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81673473)
Location: include/linux/page_ref.h:86
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
</details>
</li>
</ul>

## Differences
