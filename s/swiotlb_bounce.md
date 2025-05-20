# Function: <code>swiotlb_bounce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8141212c)
Location: lib/swiotlb.c:388
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_map_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff8145a051)
Location: lib/swiotlb.c:388
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff81478a31)
Location: lib/swiotlb.c:418
Inline: True
Inline callers:
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814818c0)
Location: lib/swiotlb.c:418
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff814818c0-ffffffff814818ee: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/swiotlb.c (ffffffff814bd710)
Location: lib/swiotlb.c:456
Inline: False
Direct callers:
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_sync_single
  - lib/swiotlb.c:swiotlb_tbl_unmap_single
  - lib/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff814bd710-ffffffff814bd73e: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8110d310)
Location: kernel/dma/swiotlb.c:442
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff8110d310-ffffffff8110d343: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81118fb0)
Location: kernel/dma/swiotlb.c:390
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff81118fb0-ffffffff81118fe3: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811239a0)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff811239a0-ffffffff811239d3: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8112f930)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff8112f930-ffffffff8112f963: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113e730)
Location: kernel/dma/swiotlb.c:409
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff8113e730-ffffffff8113e763: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81139da0)
Location: kernel/dma/swiotlb.c:427
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff81139da0-ffffffff81139dd3: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swiotlb_bounce(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8113af90)
Location: kernel/dma/swiotlb.c:348
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_device
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff8113af90-ffffffff8113b0a3: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void swiotlb_bounce(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:366
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_device
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff8115ded0-ffffffff8115e0df: swiotlb_bounce (STB_LOCAL)
ffffffff81cb04c9-ffffffff81cb051c: swiotlb_bounce.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void swiotlb_bounce(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:395
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_device
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff81187f30-ffffffff8118818e: swiotlb_bounce (STB_LOCAL)
ffffffff81e61127-ffffffff81e611ac: swiotlb_bounce.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void swiotlb_bounce(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:527
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_device
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff811c3d80-ffffffff811c3fde: swiotlb_bounce (STB_LOCAL)
ffffffff8205a849-ffffffff8205a8ce: swiotlb_bounce.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void swiotlb_bounce(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:500
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_device
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff811d6930-ffffffff811d6b8e: swiotlb_bounce (STB_LOCAL)
ffffffff820d90bd-ffffffff820d9142: swiotlb_bounce.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void swiotlb_bounce(struct device *dev, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: kernel/dma/swiotlb.c:835
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_cpu
  - kernel/dma/swiotlb.c:swiotlb_sync_single_for_device
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff811ed130-ffffffff811ed38f: swiotlb_bounce (STB_LOCAL)
ffffffff821b4a86-ffffffff821b4af2: swiotlb_bounce.cold (STB_LOCAL)
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
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffff8000101960a8)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffff8000101960a8-ffff800010196120: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f6150)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
c0000000001f6150-c0000000001f61c0: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffe00012869e)
Location: kernel/dma/swiotlb.c:408
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff811280e0)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff811280e0-ffffffff81128113: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8111a970)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff8111a970-ffffffff8111a9a3: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81125e00)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff81125e00-ffffffff81125e33: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swiotlb_bounce(phys_addr_t orig_addr, phys_addr_t tlb_addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff81132440)
Location: kernel/dma/swiotlb.c:408
Inline: False
Direct callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_sync_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_unmap_single
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
**Symbols:**

```
ffffffff81132440-ffffffff81132473: swiotlb_bounce (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t orig_addr</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
