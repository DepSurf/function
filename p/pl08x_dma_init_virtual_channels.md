# Function: <code>pl08x_dma_init_virtual_channels</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pl08x_dma_init_virtual_channels(struct pl08x_driver_data *pl08x, struct dma_device *dmadev, unsigned int channels, bool slave);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/amba-pl08x.c (ffff8000107ffd98)
Location: drivers/dma/amba-pl08x.c:2369
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
**Symbols:**

```
ffff8000107ffd98-ffff8000107fffb4: pl08x_dma_init_virtual_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pl08x_dma_init_virtual_channels(struct pl08x_driver_data *pl08x, struct dma_device *dmadev, unsigned int channels, bool slave);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/amba-pl08x.c (c0920af4)
Location: drivers/dma/amba-pl08x.c:2369
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
**Symbols:**

```
c0920af4-c0920cf8: pl08x_dma_init_virtual_channels (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
