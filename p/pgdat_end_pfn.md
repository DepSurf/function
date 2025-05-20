# Function: <code>pgdat_end_pfn</code>

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
In mm/memory_hotplug.c (ffffffff81819780)
Location: include/linux/mmzone.h:706
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81286d3d)
Location: include/linux/mmzone.h:706
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff8120e864)
Location: include/linux/mmzone.h:748
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff812b3f12)
Location: include/linux/mmzone.h:748
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff8122089e)
Location: include/linux/mmzone.h:722
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff812c97a6)
Location: include/linux/mmzone.h:722
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff818ff523)
Location: include/linux/mmzone.h:742
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff812d67f6)
Location: include/linux/mmzone.h:742
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81989623)
Location: include/linux/mmzone.h:746
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff812fb046)
Location: include/linux/mmzone.h:746
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff819e5ef7)
Location: include/linux/mmzone.h:748
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81328606)
Location: include/linux/mmzone.h:748
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81a21283)
Location: include/linux/mmzone.h:741
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8133f85b)
Location: include/linux/mmzone.h:741
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81a91932)
Location: include/linux/mmzone.h:793
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81367b4d)
Location: include/linux/mmzone.h:793
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81ac90da)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8137fdcd)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81bc17ec)
Location: include/linux/mmzone.h:779
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff813ca265)
Location: include/linux/mmzone.h:779
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
In mm/memory_hotplug.c (ffffffff81c3a7f9)
Location: include/linux/mmzone.h:829
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff813dbf25)
Location: include/linux/mmzone.h:829
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
In mm/memory_hotplug.c (ffffffff81c2cdd9)
Location: include/linux/mmzone.h:878
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff813e2eba)
Location: include/linux/mmzone.h:878
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
In mm/memory_hotplug.c (ffffffff81d4b6b6)
Location: include/linux/mmzone.h:917
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In mm/bootmem_info.c (ffffffff832de795)
Location: include/linux/mmzone.h:917
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814349ca)
Location: include/linux/mmzone.h:917
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
In mm/memory_hotplug.c (ffffffff81f1af8e)
Location: include/linux/mmzone.h:939
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In mm/bootmem_info.c (ffffffff83494089)
Location: include/linux/mmzone.h:939
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff814aeb21)
Location: include/linux/mmzone.h:939
Inline: True
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
In mm/vmscan.c (ffffffff8137fc7e)
Location: include/linux/mmzone.h:1264
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/memory_hotplug.c (ffffffff820c2e4d)
Location: include/linux/mmzone.h:1264
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In mm/bootmem_info.c (ffffffff83ec85bd)
Location: include/linux/mmzone.h:1264
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815451bc)
Location: include/linux/mmzone.h:1264
Inline: True
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
In mm/vmscan.c (ffffffff813b11fc)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/memory_hotplug.c (ffffffff82146be5)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In mm/bootmem_info.c (ffffffff836ed62d)
Location: include/linux/mmzone.h:1410
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8157cd9c)
Location: include/linux/mmzone.h:1410
Inline: True
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
In mm/vmscan.c (ffffffff813da77c)
Location: include/linux/mmzone.h:1420
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:get_pfn_folio
```
```
In mm/memory_hotplug.c (ffffffff82229375)
Location: include/linux/mmzone.h:1420
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In mm/bootmem_info.c (ffffffff8392062d)
Location: include/linux/mmzone.h:1420
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff815b56bc)
Location: include/linux/mmzone.h:1420
Inline: True
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
In mm/memory_hotplug.c (ffff800010d9cd40)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
```
```
In fs/proc/kcore.c (ffff80001044da3c)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/page_alloc.c (c0e98a88)
Location: include/linux/mmzone.h:800
Inline: True
```
```
In mm/page_ext.c (c1535480)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/page_ext.c:page_ext_init_flatmem
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
In arch/powerpc/platforms/powernv/memtrace.c (c0000000000e0aa8)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
```
```
In mm/memory_hotplug.c (c00000000042fbf4)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (c0000000005651d8)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In fs/proc/kcore.c (ffffffe0002e22e8)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81a67f4a)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff813783ad)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81a24a0a)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81368e7d)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81ad435a)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff81375e7d)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
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
In mm/memory_hotplug.c (ffffffff81ae083b)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:register_page_bootmem_info_node
```
```
In fs/proc/kcore.c (ffffffff8138992d)
Location: include/linux/mmzone.h:800
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
</details>
</li>
</ul>

## Differences
