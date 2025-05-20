# Function: <code>valid_section_nr</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f3de)
Location: include/linux/mmzone.h:1188
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a60e)
Location: include/linux/mmzone.h:1201
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
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
In mm/sparse.c (ffffffff8125dbec)
Location: include/linux/mmzone.h:1208
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff8169d660)
Location: include/linux/mmzone.h:1208
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
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
In mm/sparse.c (ffffffff8127247c)
Location: include/linux/mmzone.h:1216
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff816bde04)
Location: include/linux/mmzone.h:1216
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
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
In mm/sparse.c (ffffffff8128dc99)
Location: include/linux/mmzone.h:1289
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff816f8caf)
Location: include/linux/mmzone.h:1289
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_action
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
In mm/sparse.c (ffffffff8129d99c)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff8171d10b)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d163c)
Location: include/linux/mmzone.h:1273
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dd15c)
Location: include/linux/mmzone.h:1311
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812e49ac)
Location: include/linux/mmzone.h:1376
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8132bc2c)
Location: include/linux/mmzone.h:1413
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8139b8f8)
Location: include/linux/mmzone.h:1459
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8141b988)
Location: include/linux/mmzone.h:1791
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8144ef28)
Location: include/linux/mmzone.h:1916
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81488ae8)
Location: include/linux/mmzone.h:1927
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
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
In mm/sparse.c (ffff80001033cab8)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffff800010910ba8)
Location: include/linux/mmzone.h:1296
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
In mm/sparse.c (c000000000417c5c)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (c0000000009b1fb0)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
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
In mm/sparse.c (ffffffff81295f7c)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff816e343b)
Location: include/linux/mmzone.h:1296
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
In mm/sparse.c (ffffffff81287b8c)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff816bda7b)
Location: include/linux/mmzone.h:1296
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
In mm/sparse.c (ffffffff81293d8c)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff817105cb)
Location: include/linux/mmzone.h:1296
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
In mm/sparse.c (ffffffff812a3bec)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
```
```
In drivers/base/memory.c (ffffffff8172b72b)
Location: include/linux/mmzone.h:1296
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
</ul>

## Differences
