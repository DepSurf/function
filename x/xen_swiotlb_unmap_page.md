# Function: <code>xen_swiotlb_unmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d4ae0)
Location: drivers/xen/swiotlb-xen.c:463
Inline: False
```
**Symbols:**

```
ffffffff814d4ae0-ffffffff814d4af0: xen_swiotlb_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81525ad0)
Location: drivers/xen/swiotlb-xen.c:463
Inline: False
```
**Symbols:**

```
ffffffff81525ad0-ffffffff81525ae0: xen_swiotlb_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81551fd0)
Location: drivers/xen/swiotlb-xen.c:470
Inline: False
```
**Symbols:**

```
ffffffff81551fd0-ffffffff81551fe0: xen_swiotlb_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81566d70)
Location: drivers/xen/swiotlb-xen.c:469
Inline: False
```
**Symbols:**

```
ffffffff81566d70-ffffffff81566d80: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815caf20)
Location: drivers/xen/swiotlb-xen.c:469
Inline: False
```
**Symbols:**

```
ffffffff815caf20-ffffffff815caf30: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81603780)
Location: drivers/xen/swiotlb-xen.c:455
Inline: False
```
**Symbols:**

```
ffffffff81603780-ffffffff81603790: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161e870)
Location: drivers/xen/swiotlb-xen.c:448
Inline: False
```
**Symbols:**

```
ffffffff8161e870-ffffffff8161e880: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816517d0)
Location: drivers/xen/swiotlb-xen.c:439
Inline: False
```
**Symbols:**

```
ffffffff816517d0-ffffffff816517e0: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81673ab0)
Location: drivers/xen/swiotlb-xen.c:420
Inline: True
```
**Symbols:**

```
ffffffff81673ab0-ffffffff81673c46: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81723cd0)
Location: drivers/xen/swiotlb-xen.c:426
Inline: True
```
**Symbols:**

```
ffffffff81723cd0-ffffffff81723e66: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81740750)
Location: drivers/xen/swiotlb-xen.c:432
Inline: True
```
**Symbols:**

```
ffffffff81740750-ffffffff81740941: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817245b0)
Location: drivers/xen/swiotlb-xen.c:419
Inline: True
```
**Symbols:**

```
ffffffff817245b0-ffffffff817247a0: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817a3400)
Location: drivers/xen/swiotlb-xen.c:417
Inline: False
```
**Symbols:**

```
ffffffff817a3400-ffffffff817a35e5: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff818dd510)
Location: drivers/xen/swiotlb-xen.c:253
Inline: False
```
**Symbols:**

```
ffffffff818dd510-ffffffff818dd625: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a309d0)
Location: drivers/xen/swiotlb-xen.c:253
Inline: False
```
**Symbols:**

```
ffffffff81a309d0-ffffffff81a30ae5: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a1e0)
Location: drivers/xen/swiotlb-xen.c:253
Inline: False
```
**Symbols:**

```
ffffffff81a7a1e0-ffffffff81a7a2f5: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81acc6a0)
Location: drivers/xen/swiotlb-xen.c:253
Inline: False
```
**Symbols:**

```
ffffffff81acc6a0-ffffffff81acc7b1: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083da90)
Location: drivers/xen/swiotlb-xen.c:420
Inline: True
```
**Symbols:**

```
ffff80001083da90-ffff80001083db4c: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816397a0)
Location: drivers/xen/swiotlb-xen.c:420
Inline: True
```
**Symbols:**

```
ffffffff816397a0-ffffffff81639936: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816678f0)
Location: drivers/xen/swiotlb-xen.c:420
Inline: True
```
**Symbols:**

```
ffffffff816678f0-ffffffff81667a86: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_unmap_page(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81681eb0)
Location: drivers/xen/swiotlb-xen.c:420
Inline: True
```
**Symbols:**

```
ffffffff81681eb0-ffffffff81682046: xen_swiotlb_unmap_page (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
