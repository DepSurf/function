# Function: <code>xen_swiotlb_sync_single_for_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d4fb0)
Location: drivers/xen/swiotlb-xen.c:515
Inline: False
```
**Symbols:**

```
ffffffff814d4fb0-ffffffff814d4fc6: xen_swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81525fc0)
Location: drivers/xen/swiotlb-xen.c:515
Inline: False
```
**Symbols:**

```
ffffffff81525fc0-ffffffff81525fd6: xen_swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815524d0)
Location: drivers/xen/swiotlb-xen.c:522
Inline: False
```
**Symbols:**

```
ffffffff815524d0-ffffffff815524e6: xen_swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815667c0)
Location: drivers/xen/swiotlb-xen.c:519
Inline: False
```
**Symbols:**

```
ffffffff815667c0-ffffffff815667d6: xen_swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815ca970)
Location: drivers/xen/swiotlb-xen.c:519
Inline: False
```
**Symbols:**

```
ffffffff815ca970-ffffffff815ca986: xen_swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816031d0)
Location: drivers/xen/swiotlb-xen.c:505
Inline: False
```
**Symbols:**

```
ffffffff816031d0-ffffffff816031e6: xen_swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161e2b0)
Location: drivers/xen/swiotlb-xen.c:493
Inline: False
```
**Symbols:**

```
ffffffff8161e2b0-ffffffff8161e2c6: xen_swiotlb_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81651350)
Location: drivers/xen/swiotlb-xen.c:459
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81651350-ffffffff816514aa: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81673730)
Location: drivers/xen/swiotlb-xen.c:449
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81673730-ffffffff8167388a: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81723f47)
Location: drivers/xen/swiotlb-xen.c:455
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81723a10-ffffffff81723b6a: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81740c10)
Location: drivers/xen/swiotlb-xen.c:469
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81740c10-ffffffff81740e02: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817240f0)
Location: drivers/xen/swiotlb-xen.c:456
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff817240f0-ffffffff817242eb: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817a2f80)
Location: drivers/xen/swiotlb-xen.c:454
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff817a2f80-ffffffff817a3154: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff818dd210)
Location: drivers/xen/swiotlb-xen.c:290
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff818dd210-ffffffff818dd30f: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a30690)
Location: drivers/xen/swiotlb-xen.c:290
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81a30690-ffffffff81a3078f: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a79ea0)
Location: drivers/xen/swiotlb-xen.c:290
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81a79ea0-ffffffff81a79f9f: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81acc360)
Location: drivers/xen/swiotlb-xen.c:290
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81acc360-ffffffff81acc458: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083d850)
Location: drivers/xen/swiotlb-xen.c:449
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffff80001083d850-ffff80001083d8e4: xen_swiotlb_sync_single_for_device (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81639420)
Location: drivers/xen/swiotlb-xen.c:449
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81639420-ffffffff8163957a: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81667570)
Location: drivers/xen/swiotlb-xen.c:449
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81667570-ffffffff816676ca: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_device(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81681b30)
Location: drivers/xen/swiotlb-xen.c:449
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device
```
**Symbols:**

```
ffffffff81681b30-ffffffff81681c8a: xen_swiotlb_sync_single_for_device (STB_LOCAL)
```
</details>
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>dma_addr_t dma_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *hwdev</code>
</li>
<li>
<b>Param removed. </b>
<code>dma_addr_t dev_addr</code>
</li>
</ul>
</details>
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
