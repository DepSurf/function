# Function: <code>vchan_init</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706c00)
Location: drivers/dma/virt-dma.c:123
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81706c00-ffffffff81706cc2: vchan_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff817824b0)
Location: drivers/dma/virt-dma.c:123
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff817824b0-ffffffff81782572: vchan_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff818b8f10)
Location: drivers/dma/virt-dma.c:123
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff818b8f10-ffffffff818b8fde: vchan_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a065b0)
Location: drivers/dma/virt-dma.c:123
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81a065b0-ffffffff81a0667e: vchan_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a4f440)
Location: drivers/dma/virt-dma.c:123
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81a4f440-ffffffff81a4f50e: vchan_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a9b0e0)
Location: drivers/dma/virt-dma.c:123
Inline: False
Direct callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
**Symbols:**

```
ffffffff81a9b0e0-ffffffff81a9b1ae: vchan_init (STB_GLOBAL)
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
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffff8000107fe4c8)
Location: drivers/dma/virt-dma.c:128
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_dma_init_virtual_channels
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
**Symbols:**

```
ffff8000107fe4c8-ffff8000107fe55c: vchan_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void vchan_init(struct virt_dma_chan *vc, struct dma_device *dmadev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (c091f910)
Location: drivers/dma/virt-dma.c:128
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_dma_init_virtual_channels
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
**Symbols:**

```
c091f910-c091f9a8: vchan_init (STB_GLOBAL)
```
</details>
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
</ul>
