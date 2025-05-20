# Function: <code>xen_swiotlb_sync_single_for_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d4f90)
Location: drivers/xen/swiotlb-xen.c:507
Inline: False
```
**Symbols:**

```
ffffffff814d4f90-ffffffff814d4fa3: xen_swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81525fa0)
Location: drivers/xen/swiotlb-xen.c:507
Inline: False
```
**Symbols:**

```
ffffffff81525fa0-ffffffff81525fb3: xen_swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815524b0)
Location: drivers/xen/swiotlb-xen.c:514
Inline: False
```
**Symbols:**

```
ffffffff815524b0-ffffffff815524c3: xen_swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815667a0)
Location: drivers/xen/swiotlb-xen.c:512
Inline: False
```
**Symbols:**

```
ffffffff815667a0-ffffffff815667b3: xen_swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815ca950)
Location: drivers/xen/swiotlb-xen.c:512
Inline: False
```
**Symbols:**

```
ffffffff815ca950-ffffffff815ca963: xen_swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816031b0)
Location: drivers/xen/swiotlb-xen.c:498
Inline: False
```
**Symbols:**

```
ffffffff816031b0-ffffffff816031c3: xen_swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *hwdev, dma_addr_t dev_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161e290)
Location: drivers/xen/swiotlb-xen.c:486
Inline: False
```
**Symbols:**

```
ffffffff8161e290-ffffffff8161e2a3: xen_swiotlb_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81651190)
Location: drivers/xen/swiotlb-xen.c:447
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81651190-ffffffff816512e7: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816738f0)
Location: drivers/xen/swiotlb-xen.c:436
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff816738f0-ffffffff81673a47: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817240d7)
Location: drivers/xen/swiotlb-xen.c:442
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81723b70-ffffffff81723cc7: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817409c0)
Location: drivers/xen/swiotlb-xen.c:452
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff817409c0-ffffffff81740baf: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724350)
Location: drivers/xen/swiotlb-xen.c:439
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81724350-ffffffff8172454b: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817a31c0)
Location: drivers/xen/swiotlb-xen.c:437
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff817a31c0-ffffffff817a3394: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff818dd390)
Location: drivers/xen/swiotlb-xen.c:273
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff818dd390-ffffffff818dd48f: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a30830)
Location: drivers/xen/swiotlb-xen.c:273
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81a30830-ffffffff81a3092f: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a040)
Location: drivers/xen/swiotlb-xen.c:273
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81a7a040-ffffffff81a7a13f: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81acc500)
Location: drivers/xen/swiotlb-xen.c:273
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81acc500-ffffffff81acc5f8: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
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
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083d960)
Location: drivers/xen/swiotlb-xen.c:436
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffff80001083d960-ffff80001083d9f8: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
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
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816395e0)
Location: drivers/xen/swiotlb-xen.c:436
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff816395e0-ffffffff81639737: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
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
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81667730)
Location: drivers/xen/swiotlb-xen.c:436
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81667730-ffffffff81667887: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_swiotlb_sync_single_for_cpu(struct device *dev, dma_addr_t dma_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81681cf0)
Location: drivers/xen/swiotlb-xen.c:436
Inline: False
Direct callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff81681cf0-ffffffff81681e47: xen_swiotlb_sync_single_for_cpu (STB_LOCAL)
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
