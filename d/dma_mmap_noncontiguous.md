# Function: <code>dma_mmap_noncontiguous</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dma_mmap_noncontiguous(struct device *dev, struct vm_area_struct *vma, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138dc0)
Location: kernel/dma/mapping.c:631
Inline: True
```
**Symbols:**

```
ffffffff81138dc0-ffffffff81138e44: dma_mmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dma_mmap_noncontiguous(struct device *dev, struct vm_area_struct *vma, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115bc10)
Location: kernel/dma/mapping.c:696
Inline: True
```
**Symbols:**

```
ffffffff8115bc10-ffffffff8115bc94: dma_mmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dma_mmap_noncontiguous(struct device *dev, struct vm_area_struct *vma, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811857d0)
Location: kernel/dma/mapping.c:690
Inline: True
```
**Symbols:**

```
ffffffff811857d0-ffffffff81185881: dma_mmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dma_mmap_noncontiguous(struct device *dev, struct vm_area_struct *vma, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1140)
Location: kernel/dma/mapping.c:709
Inline: True
```
**Symbols:**

```
ffffffff811c1140-ffffffff811c11ee: dma_mmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dma_mmap_noncontiguous(struct device *dev, struct vm_area_struct *vma, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d3bb0)
Location: kernel/dma/mapping.c:713
Inline: True
```
**Symbols:**

```
ffffffff811d3bb0-ffffffff811d3c61: dma_mmap_noncontiguous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dma_mmap_noncontiguous(struct device *dev, struct vm_area_struct *vma, size_t size, struct sg_table *sgt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8850)
Location: kernel/dma/mapping.c:713
Inline: True
```
**Symbols:**

```
ffffffff811e8850-ffffffff811e8901: dma_mmap_noncontiguous (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
