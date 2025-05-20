# Function: <code>dma_direct_sync_sg_for_device</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118550)
Location: kernel/dma/direct.c:228
Inline: False
```
**Symbols:**

```
ffffffff81118550-ffffffff811185e3: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811229a0)
Location: kernel/dma/direct.c:238
Inline: False
```
**Symbols:**

```
ffffffff811229a0-ffffffff81122a27: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112ede0)
Location: kernel/dma/direct.c:238
Inline: False
```
**Symbols:**

```
ffffffff8112ede0-ffffffff8112ee67: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113d910)
Location: kernel/dma/direct.c:325
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_end_cpu_access
  - drivers/dma-buf/udmabuf.c:end_cpu_udmabuf
```
**Symbols:**

```
ffffffff8113d910-ffffffff8113d997: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81139020)
Location: kernel/dma/direct.c:337
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_device
```
**Symbols:**

```
ffffffff81139020-ffffffff811390e1: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a100)
Location: kernel/dma/direct.c:337
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_device
```
**Symbols:**

```
ffffffff8113a100-ffffffff8113a1c0: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115d190)
Location: kernel/dma/direct.c:377
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_device
```
**Symbols:**

```
ffffffff8115d190-ffffffff8115d24f: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81186ff0)
Location: kernel/dma/direct.c:409
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_device
```
**Symbols:**

```
ffffffff81186ff0-ffffffff811870cc: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2ae0)
Location: kernel/dma/direct.c:409
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_device
```
**Symbols:**

```
ffffffff811c2ae0-ffffffff811c2bbc: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d5620)
Location: kernel/dma/direct.c:408
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_device
```
**Symbols:**

```
ffffffff811d5620-ffffffff811d56fc: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:397
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_device
```
**Symbols:**

```
ffffffff821b4805-ffffffff821b4828: dma_direct_sync_sg_for_device.cold (STB_LOCAL)
ffffffff811ea510-ffffffff811ea604: dma_direct_sync_sg_for_device (STB_GLOBAL)
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
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194568)
Location: kernel/dma/direct.c:238
Inline: False
Direct callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
**Symbols:**

```
ffff800010194568-ffff800010194650: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/imx.c (0)
Location: include/linux/dma-mapping.h:219
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4790)
Location: kernel/dma/direct.c:238
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_device
```
**Symbols:**

```
c0000000001f4790-c0000000001f489c: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126670)
Location: kernel/dma/direct.c:238
Inline: False
```
**Symbols:**

```
ffffffe000126670-ffffffe000126702: dma_direct_sync_sg_for_device (STB_GLOBAL)
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
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811273c0)
Location: kernel/dma/direct.c:238
Inline: False
```
**Symbols:**

```
ffffffff811273c0-ffffffff81127447: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119e20)
Location: kernel/dma/direct.c:238
Inline: False
```
**Symbols:**

```
ffffffff81119e20-ffffffff81119ea7: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811252b0)
Location: kernel/dma/direct.c:238
Inline: False
```
**Symbols:**

```
ffffffff811252b0-ffffffff81125337: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811318f0)
Location: kernel/dma/direct.c:238
Inline: False
```
**Symbols:**

```
ffffffff811318f0-ffffffff81131977: dma_direct_sync_sg_for_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
