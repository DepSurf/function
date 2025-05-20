# Function: <code>present_section_nr</code>

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
In mm/sparse.c (ffffffff81f8c550)
Location: include/linux/mmzone.h:1106
Inline: True
Inline callers:
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:sparse_init
```
```
In mm/sparse-vmemmap.c (ffffffff81f8caba)
Location: include/linux/mmzone.h:1106
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff811efa10)
Location: include/linux/mmzone.h:1106
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:walk_memory_range
```
```
In drivers/base/node.c (ffffffff81560cde)
Location: include/linux/mmzone.h:1106
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff8156128f)
Location: include/linux/mmzone.h:1106
Inline: True
Inline callers:
  - drivers/base/memory.c:show_mem_removable
  - drivers/base/memory.c:memory_dev_init
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
In mm/sparse.c (ffffffff81fb66e1)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
```
```
In mm/sparse-vmemmap.c (ffffffff81fb682b)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8120ee73)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff815b5429)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff81fd9d3b)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:show_mem_removable
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
In mm/sparse.c (ffffffff81ff30aa)
Location: include/linux/mmzone.h:1156
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
```
```
In mm/sparse-vmemmap.c (ffffffff81ff31f4)
Location: include/linux/mmzone.h:1156
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff81220f6d)
Location: include/linux/mmzone.h:1156
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff815e4705)
Location: include/linux/mmzone.h:1156
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff8201798f)
Location: include/linux/mmzone.h:1156
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:show_mem_removable
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
In mm/sparse.c (ffffffff8121f662)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff820d5929)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8122c828)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff815f9206)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff820f9756)
Location: include/linux/mmzone.h:1178
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:show_mem_removable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a824)
Location: include/linux/mmzone.h:1191
Inline: False
Direct callers:
  - mm/sparse.c:next_present_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff826de54e)
Location: include/linux/mmzone.h:1191
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8124804a)
Location: include/linux/mmzone.h:1191
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff816612d9)
Location: include/linux/mmzone.h:1191
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff81661cdf)
Location: include/linux/mmzone.h:1191
Inline: True
Inline callers:
  - drivers/base/memory.c:show_mem_removable
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff8123a824-ffffffff8123a85d: present_section_nr (STB_LOCAL)
ffffffff81661530-ffffffff81661567: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8125ddc4)
Location: include/linux/mmzone.h:1198
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:sparse_early_usemaps_alloc_node
```
```
In mm/sparse-vmemmap.c (ffffffff82708a64)
Location: include/linux/mmzone.h:1198
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8126b99c)
Location: include/linux/mmzone.h:1198
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff8169cab3)
Location: include/linux/mmzone.h:1198
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff8169d5c2)
Location: include/linux/mmzone.h:1198
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:show_mem_removable
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff8125ddc4-ffffffff8125ddf8: present_section_nr (STB_LOCAL)
ffffffff8169ccf0-ffffffff8169cd25: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8127265a)
Location: include/linux/mmzone.h:1206
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (ffffffff81280fdc)
Location: include/linux/mmzone.h:1206
Inline: True
Inline callers:
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff816bdd6d)
Location: include/linux/mmzone.h:1206
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:removable_show
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff8127265a-ffffffff8127268e: present_section_nr (STB_LOCAL)
ffffffff816bd4a0-ffffffff816bd4d5: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8128dd58)
Location: include/linux/mmzone.h:1274
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (ffffffff8129d2c6)
Location: include/linux/mmzone.h:1274
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff816f8c70)
Location: include/linux/mmzone.h:1274
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:removable_show
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff8128dd58-ffffffff8128dd8c: present_section_nr (STB_LOCAL)
ffffffff816f82d0-ffffffff816f8305: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8129da57)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (ffffffff812aca96)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff8171d0cd)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff8129da57-ffffffff8129da8b: present_section_nr (STB_LOCAL)
ffffffff8171c6d0-ffffffff8171c705: present_section_nr (STB_LOCAL)
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
In mm/sparse.c (ffffffff812d170a)
Location: include/linux/mmzone.h:1258
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812e1a93)
Location: include/linux/mmzone.h:1258
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff817d956f)
Location: include/linux/mmzone.h:1258
Inline: True
Inline callers:
  - drivers/base/memory.c:add_memory_block
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
In mm/sparse.c (ffffffff81be8b06)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812ec9f3)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff8300d30a)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In mm/memory_hotplug.c (ffffffff812c7579)
Location: include/linux/mmzone.h:1361
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In mm/sparse.c (ffffffff81bdab32)
Location: include/linux/mmzone.h:1361
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In drivers/base/memory.c (ffffffff83218165)
Location: include/linux/mmzone.h:1361
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In mm/memory_hotplug.c (ffffffff8130c300)
Location: include/linux/mmzone.h:1398
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In mm/sparse.c (ffffffff81cc05d5)
Location: include/linux/mmzone.h:1398
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In drivers/base/memory.c (ffffffff83301baa)
Location: include/linux/mmzone.h:1398
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In mm/sparse.c (ffffffff81e729c1)
Location: include/linux/mmzone.h:1444
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In drivers/base/memory.c (ffffffff834bab6d)
Location: include/linux/mmzone.h:1444
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
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
In mm/sparse.c (ffffffff83ec55a7)
Location: include/linux/mmzone.h:1776
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/memory.c (ffffffff83ef8485)
Location: include/linux/mmzone.h:1776
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
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
In mm/sparse.c (ffffffff836ea667)
Location: include/linux/mmzone.h:1901
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/memory.c (ffffffff8371e025)
Location: include/linux/mmzone.h:1901
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
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
In mm/sparse.c (ffffffff8391da27)
Location: include/linux/mmzone.h:1912
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/memory.c (ffffffff839519f5)
Location: include/linux/mmzone.h:1912
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff80001033cc18)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/memory.c (ffff800010910b80)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffff80001033cc18-ffff80001033cc50: present_section_nr (STB_LOCAL)
ffff800010910320-ffff80001091035c: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000417d5c)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (c00000000042ef8c)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (c0000000009b1f58)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
c000000000417d5c-c000000000417db4: present_section_nr (STB_LOCAL)
c0000000009b1010-c0000000009b1068: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffe000232466)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffe000232466-ffffffe00023249e: present_section_nr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81296037)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (ffffffff812a5076)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff816e33fd)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff81296037-ffffffff8129606b: present_section_nr (STB_LOCAL)
ffffffff816e2a00-ffffffff816e2a35: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81287c47)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (ffffffff81296b46)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff816bda3d)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff81287c47-ffffffff81287c7b: present_section_nr (STB_LOCAL)
ffffffff816bd040-ffffffff816bd075: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81293e47)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (ffffffff812a2e86)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff8171058d)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff81293e47-ffffffff81293e7b: present_section_nr (STB_LOCAL)
ffffffff8170fb90-ffffffff8170fbc5: present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int present_section_nr(long unsigned int nr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812a3ca7)
Location: include/linux/mmzone.h:1281
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (ffffffff812b3116)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/memory.c (ffffffff8172b6ed)
Location: include/linux/mmzone.h:1281
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff812a3ca7-ffffffff812a3cdb: present_section_nr (STB_LOCAL)
ffffffff8172acf0-ffffffff8172ad25: present_section_nr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
