# Function: <code>map_single</code>

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
In lib/swiotlb.c (ffffffff814124bf)
Location: lib/swiotlb.c:541
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_alloc_coherent
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
In lib/swiotlb.c (ffffffff8145a9cc)
Location: lib/swiotlb.c:541
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_alloc_coherent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t map_single(struct device *hwdev, phys_addr_t phys, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81478b20)
Location: lib/swiotlb.c:573
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_sg_attrs
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81478b20-ffffffff81478b96: map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t map_single(struct device *hwdev, phys_addr_t phys, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81481e60)
Location: lib/swiotlb.c:573
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff81481e60-ffffffff81481edb: map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t map_single(struct device *hwdev, phys_addr_t phys, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814bdd10)
Location: lib/swiotlb.c:615
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_page
  - lib/swiotlb.c:swiotlb_alloc_coherent
  - lib/swiotlb.c:swiotlb_alloc_coherent
```
**Symbols:**

```
ffffffff814bdd10-ffffffff814bdd95: map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t map_single(struct device *hwdev, phys_addr_t phys, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110de50)
Location: kernel/dma/swiotlb.c:599
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_map_page
```
**Symbols:**

```
ffffffff8110de50-ffffffff8110ded9: map_single (STB_LOCAL)
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
