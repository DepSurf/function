# Function: <code>swiotlb_full</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8141280a)
Location: lib/swiotlb.c:707
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_map_sg_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145aa01)
Location: lib/swiotlb.c:707
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/swiotlb.c:swiotlb_map_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_full(struct device *dev, size_t size, enum dma_data_direction dir, int do_panic);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81478e80)
Location: lib/swiotlb.c:758
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/swiotlb.c:swiotlb_map_page
```
**Symbols:**

```
ffffffff81478e80-ffffffff81478f14: swiotlb_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_full(struct device *dev, size_t size, enum dma_data_direction dir, int do_panic);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814821d0)
Location: lib/swiotlb.c:758
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_map_page
```
**Symbols:**

```
ffffffff814821d0-ffffffff81482273: swiotlb_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void swiotlb_full(struct device *dev, size_t size, enum dma_data_direction dir, int do_panic);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be150)
Location: lib/swiotlb.c:803
Inline: True
Direct callers:
  - lib/swiotlb.c:swiotlb_map_page
```
**Symbols:**

```
ffffffff814be150-ffffffff814be1f3: swiotlb_full (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void swiotlb_full(struct device *dev, size_t size, enum dma_data_direction dir, int do_panic);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:767
Inline: True
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map_page
```
**Symbols:**

```
ffffffff8110d550-ffffffff8110d5e3: swiotlb_full (STB_LOCAL)
ffffffff8110e7bd-ffffffff8110e7e1: swiotlb_full.cold.17 (STB_LOCAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
