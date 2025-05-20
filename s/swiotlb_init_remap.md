# Function: <code>swiotlb_init_remap</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff834809f7)
Location: kernel/dma/swiotlb.c:231
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - kernel/dma/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff834809f7-ffffffff83480bc9: swiotlb_init_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff83ead1a0)
Location: kernel/dma/swiotlb.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - kernel/dma/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff83ead1a0-ffffffff83ead497: swiotlb_init_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff836d2200)
Location: kernel/dma/swiotlb.c:312
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - kernel/dma/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff836d2200-ffffffff836d24f6: swiotlb_init_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swiotlb_init_remap(bool addressing_limit, unsigned int flags, int (*remap)(void *, long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff83903eb0)
Location: kernel/dma/swiotlb.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:pci_iommu_alloc
  - kernel/dma/swiotlb.c:swiotlb_init
```
**Symbols:**

```
ffffffff83903eb0-ffffffff839042b3: swiotlb_init_remap (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
