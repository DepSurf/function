# Function: <code>swiotlb_sync_single_for_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412960)
Location: lib/swiotlb.c:847
Inline: False
```
**Symbols:**

```
ffffffff81412960-ffffffff8141296e: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a690)
Location: lib/swiotlb.c:847
Inline: False
```
**Symbols:**

```
ffffffff8145a690-ffffffff8145a69e: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81479250)
Location: lib/swiotlb.c:903
Inline: False
```
**Symbols:**

```
ffffffff81479250-ffffffff8147925e: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81482430)
Location: lib/swiotlb.c:903
Inline: False
```
**Symbols:**

```
ffffffff81482430-ffffffff8148243e: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be5c0)
Location: lib/swiotlb.c:948
Inline: False
```
**Symbols:**

```
ffffffff814be5c0-ffffffff814be5ce: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e690)
Location: kernel/dma/swiotlb.c:910
Inline: False
```
**Symbols:**

```
ffffffff8110e690-ffffffff8110e6a3: swiotlb_sync_single_for_cpu (STB_GLOBAL)
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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113bd00)
Location: kernel/dma/swiotlb.c:617
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff8113bd00-ffffffff8113bd25: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115ee00)
Location: kernel/dma/swiotlb.c:664
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff8115ee00-ffffffff8115ee25: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81188f80)
Location: kernel/dma/swiotlb.c:693
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff81188f80-ffffffff81188fbd: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811c5350)
Location: kernel/dma/swiotlb.c:870
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff811c5350-ffffffff811c538d: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811d7f20)
Location: kernel/dma/swiotlb.c:895
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff811d7f20-ffffffff811d7f5d: swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swiotlb_sync_single_for_cpu(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811ed960)
Location: kernel/dma/swiotlb.c:1459
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - kernel/dma/direct.c:dma_direct_sync_sg_for_cpu
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu
```
**Symbols:**

```
ffffffff811ed960-ffffffff811ed99d: swiotlb_sync_single_for_cpu (STB_GLOBAL)
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
