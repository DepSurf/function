# Function: <code>xen_unmap_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d49a0)
Location: drivers/xen/swiotlb-xen.c:435
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff814d49a0-ffffffff814d4ad9: xen_unmap_single.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81525980)
Location: drivers/xen/swiotlb-xen.c:435
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff81525980-ffffffff81525acc: xen_unmap_single.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81551e40)
Location: drivers/xen/swiotlb-xen.c:442
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff81551e40-ffffffff81551fc5: xen_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815668a0)
Location: drivers/xen/swiotlb-xen.c:441
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff815668a0-ffffffff81566a23: xen_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815caa50)
Location: drivers/xen/swiotlb-xen.c:441
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff815caa50-ffffffff815cabd8: xen_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xen_unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816032b0)
Location: drivers/xen/swiotlb-xen.c:427
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff816032b0-ffffffff8160342c: xen_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xen_unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161e390)
Location: drivers/xen/swiotlb-xen.c:433
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff8161e390-ffffffff8161e4ee: xen_unmap_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xen_unmap_single(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81651510)
Location: drivers/xen/swiotlb-xen.c:424
Inline: True
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page
```
**Symbols:**

```
ffffffff81651510-ffffffff8165168d: xen_unmap_single (STB_LOCAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
