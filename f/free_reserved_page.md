# Function: <code>free_reserved_page</code>

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
Location: include/linux/mm.h:1728
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8110d5f3)
Location: include/linux/mm.h:1728
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811951b1)
Location: include/linux/mm.h:1728
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff811efdf5)
Location: include/linux/mm.h:1728
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
Location: include/linux/mm.h:1844
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81114f03)
Location: include/linux/mm.h:1844
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811a91f5)
Location: include/linux/mm.h:1844
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8120f235)
Location: include/linux/mm.h:1844
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
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
Location: include/linux/mm.h:1820
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111c61b)
Location: include/linux/mm.h:1820
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811b974d)
Location: include/linux/mm.h:1820
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff81221305)
Location: include/linux/mm.h:1820
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81543903)
Location: include/linux/mm.h:1820
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
In arch/x86/mm/init_64.c (ffffffff81901a3c)
Location: include/linux/mm.h:1891
Inline: True
```
```
In kernel/kexec_core.c (ffffffff8111e54b)
Location: include/linux/mm.h:1891
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811c17cd)
Location: include/linux/mm.h:1891
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8122ca6d)
Location: include/linux/mm.h:1891
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815577b2)
Location: include/linux/mm.h:1891
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
In arch/x86/mm/init_64.c (ffffffff8198ba6c)
Location: include/linux/mm.h:1993
Inline: True
```
```
In kernel/kexec_core.c (ffffffff81129cab)
Location: include/linux/mm.h:1993
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811d5bed)
Location: include/linux/mm.h:1993
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8124829e)
Location: include/linux/mm.h:1993
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815bb8f0)
Location: include/linux/mm.h:1993
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
In arch/x86/mm/init_64.c (ffffffff819e8361)
Location: include/linux/mm.h:2082
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81137bfb)
Location: include/linux/mm.h:2082
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff811f702d)
Location: include/linux/mm.h:2082
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8126bcce)
Location: include/linux/mm.h:2082
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff815f3e4e)
Location: include/linux/mm.h:2082
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
In arch/x86/mm/init_64.c (ffffffff81a23951)
Location: include/linux/mm.h:2152
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8114341b)
Location: include/linux/mm.h:2152
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812093cd)
Location: include/linux/mm.h:2152
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812805ce)
Location: include/linux/mm.h:2152
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8160ecb2)
Location: include/linux/mm.h:2152
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
In arch/x86/mm/init_64.c (ffffffff81a93c7b)
Location: include/linux/mm.h:2147
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8114e75b)
Location: include/linux/mm.h:2147
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812728e9)
Location: include/linux/mm.h:2147
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8129c90c)
Location: include/linux/mm.h:2147
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81642a75)
Location: include/linux/mm.h:2147
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
In arch/x86/mm/init_64.c (ffffffff81acb55b)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115a46b)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81281749)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812ac5ac)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8166501d)
Location: include/linux/mm.h:2119
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
In arch/x86/mm/init_64.c (ffffffff81bc3a5d)
Location: include/linux/mm.h:2388
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116b23b)
Location: include/linux/mm.h:2388
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812b3c33)
Location: include/linux/mm.h:2388
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812e164c)
Location: include/linux/mm.h:2388
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81713fc4)
Location: include/linux/mm.h:2388
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
In arch/x86/mm/init_64.c (ffffffff81c3c988)
Location: include/linux/mm.h:2404
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116797b)
Location: include/linux/mm.h:2404
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812bf6e7)
Location: include/linux/mm.h:2404
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812ec59c)
Location: include/linux/mm.h:2404
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81730f94)
Location: include/linux/mm.h:2404
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
In arch/x86/mm/init_64.c (ffffffff81c2ee64)
Location: include/linux/mm.h:2397
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8116870b)
Location: include/linux/mm.h:2397
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff812c4d67)
Location: include/linux/mm.h:2397
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812c6e3c)
Location: include/linux/mm.h:2397
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81714c98)
Location: include/linux/mm.h:2397
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
In arch/x86/mm/init_64.c (ffffffff81d4d565)
Location: include/linux/mm.h:2426
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8118e43b)
Location: include/linux/mm.h:2426
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81309217)
Location: include/linux/mm.h:2426
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff8136cb6c)
Location: include/linux/mm.h:2426
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81791bbe)
Location: include/linux/mm.h:2426
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
In arch/x86/mm/init_64.c (ffffffff81f1d26f)
Location: include/linux/mm.h:2503
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811bd9eb)
Location: include/linux/mm.h:2503
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81371714)
Location: include/linux/mm.h:2503
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff813eaf06)
Location: include/linux/mm.h:2503
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff818ca840)
Location: include/linux/mm.h:2503
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
In arch/x86/mm/init_64.c (ffffffff820c53d5)
Location: include/linux/mm.h:2667
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff811ffb1f)
Location: include/linux/mm.h:2667
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_shrink_memory
```
```
In mm/page_alloc.c (ffffffff813eee44)
Location: include/linux/mm.h:2667
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff81473106)
Location: include/linux/mm.h:2667
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a1b3ec)
Location: include/linux/mm.h:2667
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
In arch/x86/mm/init_64.c (ffffffff82149435)
Location: include/linux/mm.h:2992
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff812138b0)
Location: include/linux/mm.h:2992
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
```
```
In mm/page_alloc.c (ffffffff81422c14)
Location: include/linux/mm.h:2992
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff814a7876)
Location: include/linux/mm.h:2992
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81a64580)
Location: include/linux/mm.h:2992
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
In arch/x86/mm/init_64.c (ffffffff8222bef5)
Location: include/linux/mm.h:3113
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8122b80f)
Location: include/linux/mm.h:3113
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
```
```
In mm/page_alloc.c (ffffffff8144faf4)
Location: include/linux/mm.h:3113
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/bootmem_info.c (ffffffff814d88a6)
Location: include/linux/mm.h:3113
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81ab6de0)
Location: include/linux/mm.h:3113
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
In kernel/kexec_core.c (ffff8000101c9aec)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffff800010319bd4)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffff80001034e130)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffff80001082ee04)
Location: include/linux/mm.h:2119
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
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (c05344d8)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
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
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range
```
```
In arch/powerpc/kernel/fadump.c (c00000000004c16c)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/powerpc/kernel/fadump.c:fadump_release_reserved_area
```
```
In arch/powerpc/mm/init_64.c (c000000000088e68)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:vmemmap_free
```
```
In kernel/kexec_core.c (c000000000232580)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (c0000000003ecc64)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (c00000000042e890)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
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
In mm/page_alloc.c (ffffffe00021f6a4)
Location: include/linux/mm.h:2119
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
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81152a8b)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81279d99)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812a4b8c)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8162abb0)
Location: include/linux/mm.h:2119
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
In arch/x86/mm/init_64.c (ffffffff81a2688d)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff81145d6b)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff8126bc89)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff8129665c)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
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
In arch/x86/mm/init_64.c (ffffffff81ad67db)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115093b)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81277b39)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812a299c)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff81658e5d)
Location: include/linux/mm.h:2119
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
In arch/x86/mm/init_64.c (ffffffff81ae2c9b)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:free_pagetable
```
```
In kernel/kexec_core.c (ffffffff8115d75b)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - kernel/kexec_core.c:crash_free_reserved_phys_range
```
```
In mm/page_alloc.c (ffffffff81287729)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/page_alloc.c:free_reserved_area
```
```
In mm/memory_hotplug.c (ffffffff812b2c2c)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In drivers/xen/balloon.c (ffffffff8167346d)
Location: include/linux/mm.h:2119
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_process
```
</details>
</li>
</ul>

## Differences
