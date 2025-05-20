# Function: <code>swiotlb_sync_single_for_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81412970)
Location: lib/swiotlb.c:855
Inline: False
```
**Symbols:**

```
ffffffff81412970-ffffffff81412981: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a6a0)
Location: lib/swiotlb.c:855
Inline: False
```
**Symbols:**

```
ffffffff8145a6a0-ffffffff8145a6b1: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81479260)
Location: lib/swiotlb.c:911
Inline: False
```
**Symbols:**

```
ffffffff81479260-ffffffff81479271: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81482440)
Location: lib/swiotlb.c:911
Inline: False
```
**Symbols:**

```
ffffffff81482440-ffffffff81482451: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814be5d0)
Location: lib/swiotlb.c:956
Inline: False
```
**Symbols:**

```
ffffffff814be5d0-ffffffff814be5e1: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110e6b0)
Location: kernel/dma/swiotlb.c:917
Inline: False
```
**Symbols:**

```
ffffffff8110e6b0-ffffffff8110e6c6: swiotlb_sync_single_for_device (STB_GLOBAL)
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
void swiotlb_sync_single_for_device(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113bcd0)
Location: kernel/dma/swiotlb.c:608
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
```
**Symbols:**

```
ffffffff8113bcd0-ffffffff8113bcf2: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8115edd0)
Location: kernel/dma/swiotlb.c:652
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
```
**Symbols:**

```
ffffffff8115edd0-ffffffff8115edf3: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81188f40)
Location: kernel/dma/swiotlb.c:684
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
```
**Symbols:**

```
ffffffff81188f40-ffffffff81188f7a: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811c5300)
Location: kernel/dma/swiotlb.c:861
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
```
**Symbols:**

```
ffffffff811c5300-ffffffff811c533a: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811d7ed0)
Location: kernel/dma/swiotlb.c:886
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
```
**Symbols:**

```
ffffffff811d7ed0-ffffffff811d7f0a: swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swiotlb_sync_single_for_device(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811ed910)
Location: kernel/dma/swiotlb.c:1450
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
  - kernel/dma/direct.c:dma_direct_sync_sg_for_device
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device
```
**Symbols:**

```
ffffffff811ed910-ffffffff811ed94a: swiotlb_sync_single_for_device (STB_GLOBAL)
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
