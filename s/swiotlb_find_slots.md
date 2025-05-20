# Function: <code>swiotlb_find_slots</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int swiotlb_find_slots(struct device *dev, phys_addr_t orig_addr, size_t alloc_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115e310)
Location: kernel/dma/swiotlb.c:461
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff8115e310-ffffffff8115e6b9: swiotlb_find_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int swiotlb_find_slots(struct device *dev, phys_addr_t orig_addr, size_t alloc_size, unsigned int alloc_align_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81188480)
Location: kernel/dma/swiotlb.c:490
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff81188480-ffffffff81188895: swiotlb_find_slots (STB_LOCAL)
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
In kernel/dma/swiotlb.c (ffffffff811c4f29)
Location: kernel/dma/swiotlb.c:713
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
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
In kernel/dma/swiotlb.c (ffffffff811d7c89)
Location: kernel/dma/swiotlb.c:725
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int swiotlb_find_slots(struct device *dev, phys_addr_t orig_addr, size_t alloc_size, unsigned int alloc_align_mask, struct io_tlb_pool **retpool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:1127
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff811ec570-ffffffff811ec7c0: swiotlb_find_slots (STB_LOCAL)
ffffffff821b4958-ffffffff821b4974: swiotlb_find_slots.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int alloc_align_mask</code>
</li>
</ul>
</details>
</li>
</ul>
