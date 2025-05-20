# Function: <code>dma_direct_sync_sg_for_cpu</code>

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
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811185f0)
Location: kernel/dma/direct.c:265
Inline: False
```
**Symbols:**

```
ffffffff811185f0-ffffffff81118680: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122a30)
Location: kernel/dma/direct.c:277
Inline: False
```
**Symbols:**

```
ffffffff81122a30-ffffffff81122ab4: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112ee70)
Location: kernel/dma/direct.c:277
Inline: False
```
**Symbols:**

```
ffffffff8112ee70-ffffffff8112eef4: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113d9a0)
Location: kernel/dma/direct.c:364
Inline: False
Direct callers:
  - drivers/dma-buf/heaps/heap-helpers.c:dma_heap_dma_buf_begin_cpu_access
  - drivers/dma-buf/udmabuf.c:begin_cpu_udmabuf
```
**Symbols:**

```
ffffffff8113d9a0-ffffffff8113da24: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811390f0)
Location: kernel/dma/direct.c:360
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff811390f0-ffffffff811391aa: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113a1c0)
Location: kernel/dma/direct.c:360
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff8113a1c0-ffffffff8113a280: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8115d250)
Location: kernel/dma/direct.c:400
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff8115d250-ffffffff8115d30f: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811870d0)
Location: kernel/dma/direct.c:432
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff811870d0-ffffffff811871ac: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811c2bd0)
Location: kernel/dma/direct.c:432
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff811c2bd0-ffffffff811c2cac: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811d5710)
Location: kernel/dma/direct.c:431
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff811d5710-ffffffff811d57ec: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:420
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_sync_sg_for_cpu
```
**Symbols:**

```
ffffffff821b4828-ffffffff821b484b: dma_direct_sync_sg_for_cpu.cold (STB_LOCAL)
ffffffff811ea620-ffffffff811ea714: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
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
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff8000101946f0)
Location: kernel/dma/direct.c:277
Inline: False
Direct callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
**Symbols:**

```
ffff8000101946f0-ffff8000101947c8: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/imx.c (0)
Location: include/linux/dma-mapping.h:250
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/dma-mapping.h:250
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f48a0)
Location: kernel/dma/direct.c:277
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_sg_for_cpu
```
**Symbols:**

```
c0000000001f48a0-c0000000001f49ac: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126702)
Location: kernel/dma/direct.c:277
Inline: False
```
**Symbols:**

```
ffffffe000126702-ffffffe000126794: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
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
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127450)
Location: kernel/dma/direct.c:277
Inline: False
```
**Symbols:**

```
ffffffff81127450-ffffffff811274d4: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119eb0)
Location: kernel/dma/direct.c:277
Inline: False
```
**Symbols:**

```
ffffffff81119eb0-ffffffff81119f34: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125340)
Location: kernel/dma/direct.c:277
Inline: False
```
**Symbols:**

```
ffffffff81125340-ffffffff811253c4: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nents, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131980)
Location: kernel/dma/direct.c:277
Inline: False
```
**Symbols:**

```
ffffffff81131980-ffffffff81131a04: dma_direct_sync_sg_for_cpu (STB_GLOBAL)
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
