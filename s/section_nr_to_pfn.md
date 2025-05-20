# Function: <code>section_nr_to_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8198f0b8)
Location: include/linux/mmzone.h:1097
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff812483fa)
Location: include/linux/mmzone.h:1097
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
```
```
In drivers/base/node.c (ffffffff816611f7)
Location: include/linux/mmzone.h:1097
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/base/memory.c (ffffffff816620bf)
Location: include/linux/mmzone.h:1097
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:memory_block_action
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
In mm/sparse.c (ffffffff8125dc92)
Location: include/linux/mmzone.h:1096
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_init_one_section
```
```
In mm/memory_hotplug.c (ffffffff8126beef)
Location: include/linux/mmzone.h:1096
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
```
```
In drivers/base/node.c (ffffffff8169c9d8)
Location: include/linux/mmzone.h:1096
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
```
```
In drivers/base/memory.c (ffffffff8169d89f)
Location: include/linux/mmzone.h:1096
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:show_valid_zones
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
In mm/sparse.c (ffffffff812724ff)
Location: include/linux/mmzone.h:1104
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory_hotplug.c (ffffffff8128073b)
Location: include/linux/mmzone.h:1104
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
```
```
In drivers/base/node.c (ffffffff816bd228)
Location: include/linux/mmzone.h:1104
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816be03f)
Location: include/linux/mmzone.h:1104
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
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
In mm/sparse.c (ffffffff81a9745d)
Location: include/linux/mmzone.h:1144
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1144
Inline: True
```
```
In drivers/base/node.c (ffffffff816f7fe9)
Location: include/linux/mmzone.h:1144
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:register_mem_sect_under_node
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816f8ed2)
Location: include/linux/mmzone.h:1144
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
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
In mm/sparse.c (ffffffff81aced3f)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1151
Inline: True
```
```
In drivers/base/node.c (ffffffff8171b37b)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8171d242)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_subsys_offline
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
In mm/sparse.c (ffffffff81bc7724)
Location: include/linux/mmzone.h:1125
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_one_section
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1125
Inline: True
```
```
In drivers/base/node.c (ffffffff817d7421)
Location: include/linux/mmzone.h:1125
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817d90d8)
Location: include/linux/mmzone.h:1125
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
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
In mm/sparse.c (ffffffff81c40450)
Location: include/linux/mmzone.h:1163
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_one_section
```
```
In mm/memory_hotplug.c (ffffffff812eb95c)
Location: include/linux/mmzone.h:1163
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
```
```
In drivers/base/node.c (ffffffff817ebe95)
Location: include/linux/mmzone.h:1163
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817ed855)
Location: include/linux/mmzone.h:1163
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:phys_device_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
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
In mm/memory_hotplug.c (ffffffff812c6636)
Location: include/linux/mmzone.h:1227
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
```
```
In mm/sparse.c (ffffffff81c324df)
Location: include/linux/mmzone.h:1227
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_one_section
```
```
In drivers/base/node.c (ffffffff817d06b5)
Location: include/linux/mmzone.h:1227
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff817d2195)
Location: include/linux/mmzone.h:1227
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:phys_device_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
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
In mm/memory_hotplug.c (ffffffff8130af87)
Location: include/linux/mmzone.h:1265
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
```
```
In mm/sparse.c (ffffffff81d50eea)
Location: include/linux/mmzone.h:1265
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_one_section
```
```
In drivers/base/node.c (ffffffff8185b045)
Location: include/linux/mmzone.h:1265
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8185d2a5)
Location: include/linux/mmzone.h:1265
Inline: True
Inline callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:phys_device_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
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
In mm/memory_hotplug.c (ffffffff81374677)
Location: include/linux/mmzone.h:1308
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
```
```
In mm/sparse.c (ffffffff81f210f6)
Location: include/linux/mmzone.h:1308
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_one_section
```
```
In drivers/base/node.c (ffffffff819a1fad)
Location: include/linux/mmzone.h:1308
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff819a4a45)
Location: include/linux/mmzone.h:1308
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:phys_device_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
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
In mm/memory_hotplug.c (ffffffff813f17e7)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
```
```
In mm/sparse.c (ffffffff820cad0d)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/node.c (ffffffff81b13f1d)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff81b16b15)
Location: include/linux/mmzone.h:1624
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:phys_device_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
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
In mm/compaction.c (ffffffff813dbaf4)
Location: include/linux/mmzone.h:1749
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
```
```
In mm/memory_hotplug.c (ffffffff81425327)
Location: include/linux/mmzone.h:1749
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
```
```
In mm/sparse.c (ffffffff8214efa5)
Location: include/linux/mmzone.h:1749
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/node.c (ffffffff81b62c4d)
Location: include/linux/mmzone.h:1749
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff81b65885)
Location: include/linux/mmzone.h:1749
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:phys_device_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
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
In mm/compaction.c (ffffffff81405a54)
Location: include/linux/mmzone.h:1759
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
```
```
In mm/memory_hotplug.c (ffffffff81452567)
Location: include/linux/mmzone.h:1759
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
```
```
In mm/sparse.c (ffffffff82231e28)
Location: include/linux/mmzone.h:1759
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/node.c (ffffffff81bb675d)
Location: include/linux/mmzone.h:1759
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff81bb9705)
Location: include/linux/mmzone.h:1759
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:phys_device_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
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
In mm/sparse.c (ffff800010da0938)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In drivers/base/node.c (ffff80001090ecb8)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffff800010910afc)
Location: include/linux/mmzone.h:1151
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
In mm/sparse.c (c000000000eed724)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1151
Inline: True
```
```
In drivers/base/node.c (c0000000009af7ac)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (c0000000009b219c)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
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
In mm/sparse.c (ffffffe0000183d2)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_decode_mem_map
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
In mm/sparse.c (ffffffff81a6dbaf)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1151
Inline: True
```
```
In drivers/base/node.c (ffffffff816e16ab)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816e3572)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_subsys_offline
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
In mm/sparse.c (ffffffff81a2a0f6)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1151
Inline: True
```
```
In drivers/base/node.c (ffffffff816bbceb)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff816bdbb2)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_subsys_offline
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
In mm/sparse.c (ffffffff81ad9fbf)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1151
Inline: True
```
```
In drivers/base/node.c (ffffffff8170ebdb)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff81710702)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_subsys_offline
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
In mm/sparse.c (ffffffff81ae6475)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:sparse_init_nid
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/mmzone.h:1151
Inline: True
```
```
In drivers/base/node.c (ffffffff8172999b)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
```
In drivers/base/memory.c (ffffffff8172b862)
Location: include/linux/mmzone.h:1151
Inline: True
Inline callers:
  - drivers/base/memory.c:init_memory_block
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
</ul>

## Differences
