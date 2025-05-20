# Function: <code>pfn_present</code>

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
In mm/sparse.c (ffffffff81f8c829)
Location: include/linux/mmzone.h:1135
Inline: True
Inline callers:
  - mm/sparse.c:node_memmap_size_bytes
```
```
In drivers/base/node.c (ffffffff81560a43)
Location: include/linux/mmzone.h:1135
Inline: True
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
In mm/sparse.c (ffffffff81fb6554)
Location: include/linux/mmzone.h:1207
Inline: True
Inline callers:
  - mm/sparse.c:node_memmap_size_bytes
```
```
In drivers/base/node.c (ffffffff815b5174)
Location: include/linux/mmzone.h:1207
Inline: True
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
In mm/sparse.c (ffffffff81ff2f1d)
Location: include/linux/mmzone.h:1185
Inline: True
Inline callers:
  - mm/sparse.c:node_memmap_size_bytes
```
```
In drivers/base/node.c (ffffffff815e4424)
Location: include/linux/mmzone.h:1185
Inline: True
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
In mm/sparse.c (ffffffff820d5629)
Location: include/linux/mmzone.h:1226
Inline: True
Inline callers:
  - mm/sparse.c:node_memmap_size_bytes
```
```
In drivers/base/node.c (ffffffff815f901e)
Location: include/linux/mmzone.h:1226
Inline: True
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
In mm/sparse.c (ffffffff826de214)
Location: include/linux/mmzone.h:1239
Inline: True
Inline callers:
  - mm/sparse.c:node_memmap_size_bytes
```
```
In drivers/base/node.c (ffffffff816610dc)
Location: include/linux/mmzone.h:1239
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff8169c8ab)
Location: include/linux/mmzone.h:1246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff816bc73d)
Location: include/linux/mmzone.h:1254
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
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
In mm/shuffle.c (ffffffff81a957dc)
Location: include/linux/mmzone.h:1355
Inline: True
```
```
In drivers/base/node.c (ffffffff816f6f88)
Location: include/linux/mmzone.h:1355
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
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
In mm/shuffle.c (ffffffff81acd0bf)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In drivers/base/node.c (ffffffff8171b394)
Location: include/linux/mmzone.h:1362
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/shuffle.c (ffff800010da00e4)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In drivers/base/node.c (ffff80001090ece8)
Location: include/linux/mmzone.h:1362
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
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
In arch/powerpc/platforms/pseries/hotplug-memory.c (c0000000000fc1c8)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In mm/shuffle.c (c000000000eecd1c)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In drivers/base/node.c (c0000000009af7d4)
Location: include/linux/mmzone.h:1362
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
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
In mm/shuffle.c (ffffffe000047478)
Location: include/linux/mmzone.h:1362
Inline: True
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
In mm/shuffle.c (ffffffff81a6bf2f)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In drivers/base/node.c (ffffffff816e16c4)
Location: include/linux/mmzone.h:1362
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
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
In mm/shuffle.c (ffffffff81a28476)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In drivers/base/node.c (ffffffff816bbd04)
Location: include/linux/mmzone.h:1362
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
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
In mm/shuffle.c (ffffffff81ad833f)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In drivers/base/node.c (ffffffff8170ebf4)
Location: include/linux/mmzone.h:1362
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
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
In mm/shuffle.c (ffffffff81ae47fa)
Location: include/linux/mmzone.h:1362
Inline: True
```
```
In drivers/base/node.c (ffffffff817299b4)
Location: include/linux/mmzone.h:1362
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_sect_under_node
```
</details>
</li>
</ul>

## Differences
