# Function: <code>present_section</code>

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
In mm/sparse.c (ffffffff81f8c56c)
Location: include/linux/mmzone.h:1101
Inline: True
Inline callers:
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:node_memmap_size_bytes
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/sparse-vmemmap.c (ffffffff81f8cae5)
Location: include/linux/mmzone.h:1101
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff811efa32)
Location: include/linux/mmzone.h:1101
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:test_pages_in_a_zone
  - mm/memory_hotplug.c:walk_memory_range
```
```
In drivers/base/node.c (ffffffff81560a6d)
Location: include/linux/mmzone.h:1101
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff815612ab)
Location: include/linux/mmzone.h:1101
Inline: True
Inline callers:
  - drivers/base/memory.c:show_mem_removable
  - drivers/base/memory.c:unregister_memory_section
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
In mm/sparse.c (ffffffff81899555)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:node_memmap_size_bytes
```
```
In mm/sparse-vmemmap.c (ffffffff81fb6851)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8120ee91)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff815b5448)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff81fd9d53)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:unregister_memory_section
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
In mm/sparse.c (ffffffff818cdc0d)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:node_memmap_size_bytes
```
```
In mm/sparse-vmemmap.c (ffffffff81ff321a)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff81220f8b)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff815e4724)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
```
```
In drivers/base/memory.c (ffffffff820179a7)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:unregister_memory_section
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
In mm/sparse.c (ffffffff819050bb)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:next_present_section_nr
  - mm/sparse.c:node_memmap_size_bytes
```
```
In mm/sparse-vmemmap.c (ffffffff820d594f)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8122c846)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff815f9224)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff820f9771)
Location: include/linux/mmzone.h:1173
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:show_mem_removable
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
In mm/sparse.c (ffffffff8198f09d)
Location: include/linux/mmzone.h:1186
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_init
  - mm/sparse.c:node_memmap_size_bytes
  - mm/sparse.c:present_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff826de583)
Location: include/linux/mmzone.h:1186
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8124807e)
Location: include/linux/mmzone.h:1186
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff81661303)
Location: include/linux/mmzone.h:1186
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff816622a5)
Location: include/linux/mmzone.h:1186
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:show_mem_removable
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
In mm/sparse.c (ffffffff819eb799)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_one_section
  - mm/sparse.c:present_section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff82708a92)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:sparse_mem_maps_populate_node
```
```
In mm/memory_hotplug.c (ffffffff8126b9b1)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff8169cac8)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - drivers/base/node.c:link_mem_sections
```
```
In drivers/base/memory.c (ffffffff8169da95)
Location: include/linux/mmzone.h:1193
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:show_mem_removable
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
In mm/sparse.c (ffffffff8127267a)
Location: include/linux/mmzone.h:1201
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81280ff1)
Location: include/linux/mmzone.h:1201
Inline: True
Inline callers:
  - mm/memory_hotplug.c:walk_memory_range
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff816bc762)
Location: include/linux/mmzone.h:1201
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816be205)
Location: include/linux/mmzone.h:1201
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:removable_show
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
In mm/shuffle.c (ffffffff81a9580a)
Location: include/linux/mmzone.h:1269
Inline: True
```
```
In mm/sparse.c (ffffffff8128dd78)
Location: include/linux/mmzone.h:1269
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff8129d2e3)
Location: include/linux/mmzone.h:1269
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff816f6fb3)
Location: include/linux/mmzone.h:1269
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816f8c87)
Location: include/linux/mmzone.h:1269
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
  - drivers/base/memory.c:removable_show
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
In mm/shuffle.c (ffffffff81acd0ed)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (ffffffff8129da77)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812acab3)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff8171b3bf)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8171d0e4)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
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
In mm/sparse.c (ffffffff812d1712)
Location: include/linux/mmzone.h:1253
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812e1ab7)
Location: include/linux/mmzone.h:1253
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff817d7477)
Location: include/linux/mmzone.h:1253
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817d9584)
Location: include/linux/mmzone.h:1253
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
In mm/sparse.c (ffffffff81be8b0e)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812eca17)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff817ebef5)
Location: include/linux/mmzone.h:1291
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8300d342)
Location: include/linux/mmzone.h:1291
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
In mm/memory_hotplug.c (ffffffff812c759d)
Location: include/linux/mmzone.h:1356
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In mm/sparse.c (ffffffff81bdab3a)
Location: include/linux/mmzone.h:1356
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In drivers/base/node.c (ffffffff817d0715)
Location: include/linux/mmzone.h:1356
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8321819d)
Location: include/linux/mmzone.h:1356
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
In mm/memory_hotplug.c (ffffffff8130c324)
Location: include/linux/mmzone.h:1393
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In mm/sparse.c (ffffffff81cc05dd)
Location: include/linux/mmzone.h:1393
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In drivers/base/node.c (ffffffff8185b0ab)
Location: include/linux/mmzone.h:1393
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff83301be2)
Location: include/linux/mmzone.h:1393
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
In mm/sparse.c (ffffffff81e729c9)
Location: include/linux/mmzone.h:1439
Inline: True
Inline callers:
  - mm/sparse.c:next_present_section_nr
```
```
In drivers/base/node.c (ffffffff819a2014)
Location: include/linux/mmzone.h:1439
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff834babb4)
Location: include/linux/mmzone.h:1439
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
In mm/sparse.c (ffffffff83ec55df)
Location: include/linux/mmzone.h:1771
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
In drivers/base/node.c (ffffffff81b13f84)
Location: include/linux/mmzone.h:1771
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff83ef84b0)
Location: include/linux/mmzone.h:1771
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
In mm/sparse.c (ffffffff836ea69f)
Location: include/linux/mmzone.h:1896
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
In drivers/base/node.c (ffffffff81b62cb4)
Location: include/linux/mmzone.h:1896
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8371e050)
Location: include/linux/mmzone.h:1896
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
In mm/sparse.c (ffffffff8391da5f)
Location: include/linux/mmzone.h:1907
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
In drivers/base/node.c (ffffffff81bb67c4)
Location: include/linux/mmzone.h:1907
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff83951a20)
Location: include/linux/mmzone.h:1907
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffff800010da010c)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (ffff80001033cc30)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In drivers/base/node.c (ffff80001090ece8)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffff800010910b80)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fc20c)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/shuffle.c (c000000000eecd58)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (c000000000417d98)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (c00000000042efac)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (c0000000009af810)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (c0000000009b1f78)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
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
In mm/shuffle.c (ffffffe0000474aa)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (ffffffe000232482)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
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
In mm/shuffle.c (ffffffff81a6bf5d)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (ffffffff81296057)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812a5093)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff816e16ef)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816e3414)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
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
In mm/shuffle.c (ffffffff81a284a4)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (ffffffff81287c67)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff81296b63)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff816bbd2f)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816bda54)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
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
In mm/shuffle.c (ffffffff81ad836d)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (ffffffff81293e67)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812a2ea3)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff8170ec1f)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff817105a4)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
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
In mm/shuffle.c (ffffffff81ae4828)
Location: include/linux/mmzone.h:1276
Inline: True
```
```
In mm/sparse.c (ffffffff812a3cc7)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/sparse.c:present_section_nr
```
```
In mm/memory_hotplug.c (ffffffff812b3133)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - mm/memory_hotplug.c:test_pages_in_a_zone
```
```
In drivers/base/node.c (ffffffff817299df)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8172b704)
Location: include/linux/mmzone.h:1276
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
</ul>

## Differences
