# Function: <code>dma_get_min_align_mask</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113bbb2)
Location: include/linux/dma-mapping.h:545
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_bounce
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
In kernel/dma/swiotlb.c (ffffffff8115ec86)
Location: include/linux/dma-mapping.h:525
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_find_slots
  - kernel/dma/swiotlb.c:swiotlb_bounce
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
In kernel/dma/swiotlb.c (ffffffff81189245)
Location: include/linux/dma-mapping.h:525
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_max_mapping_size
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_find_slots
  - kernel/dma/swiotlb.c:swiotlb_bounce
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
In kernel/dma/swiotlb.c (ffffffff811c5635)
Location: include/linux/dma-mapping.h:530
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_max_mapping_size
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
  - kernel/dma/swiotlb.c:swiotlb_bounce
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
In kernel/dma/swiotlb.c (ffffffff811d8215)
Location: include/linux/dma-mapping.h:531
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_max_mapping_size
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_do_find_slots
  - kernel/dma/swiotlb.c:swiotlb_bounce
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
In kernel/dma/swiotlb.c (ffffffff811edc35)
Location: include/linux/dma-mapping.h:524
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_max_mapping_size
  - kernel/dma/swiotlb.c:swiotlb_release_slots
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
  - kernel/dma/swiotlb.c:swiotlb_search_pool_area
  - kernel/dma/swiotlb.c:swiotlb_bounce
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
