# Function: <code>swiotlb_map_sg_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412a50)
Location: lib/swiotlb.c:879
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_sg
```
**Symbols:**

```
ffffffff81412a50-ffffffff81412b80: swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a930)
Location: lib/swiotlb.c:879
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_map_sg
```
**Symbols:**

```
ffffffff8145a930-ffffffff8145aa60: swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81479110)
Location: lib/swiotlb.c:935
Inline: False
```
**Symbols:**

```
ffffffff81479110-ffffffff8147921d: swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81482540)
Location: lib/swiotlb.c:935
Inline: True
```
**Symbols:**

```
ffffffff81482540-ffffffff8148264d: swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be450)
Location: lib/swiotlb.c:980
Inline: True
```
**Symbols:**

```
ffffffff814be450-ffffffff814be57a: swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e290)
Location: kernel/dma/swiotlb.c:940
Inline: True
```
**Symbols:**

```
ffffffff8110e290-ffffffff8110e3d4: swiotlb_map_sg_attrs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
