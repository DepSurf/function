# Function: <code>dma_mmap_from_dev_coherent</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dma_mmap_from_dev_coherent(struct device *dev, struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffff81123530)
Location: kernel/dma/coherent.c:284
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
**Symbols:**

```
ffffffff81123530-ffffffff8112354c: dma_mmap_from_dev_coherent (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dma_mmap_from_dev_coherent(struct device *dev, struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffff800010195e00)
Location: kernel/dma/coherent.c:274
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - drivers/iommu/dma-iommu.c:iommu_dma_mmap
```
**Symbols:**

```
ffff800010195e00-ffff800010195e64: dma_mmap_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dma_mmap_from_dev_coherent(struct device *dev, struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c03e2748)
Location: kernel/dma/coherent.c:274
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
**Symbols:**

```
c03e2748-c03e277c: dma_mmap_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dma_mmap_from_dev_coherent(struct device *dev, struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (c0000000001f5f10)
Location: kernel/dma/coherent.c:274
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
**Symbols:**

```
c0000000001f5f10-c0000000001f5f30: dma_mmap_from_dev_coherent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dma_mmap_from_dev_coherent(struct device *dev, struct vm_area_struct *vma, void *vaddr, size_t size, int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/coherent.c (ffffffe0001278d2)
Location: kernel/dma/coherent.c:274
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
```
**Symbols:**

```
ffffffe0001278d2-ffffffe000127922: dma_mmap_from_dev_coherent (STB_GLOBAL)
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
