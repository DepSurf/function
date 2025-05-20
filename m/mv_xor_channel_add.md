# Function: <code>mv_xor_channel_add</code>

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
struct mv_xor_chan *mv_xor_channel_add(struct mv_xor_device *xordev, struct platform_device *pdev, int idx, dma_cap_mask_t cap_mask, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/mv_xor.c (ffff800010807558)
Location: drivers/dma/mv_xor.c:1034
Inline: False
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
**Symbols:**

```
ffff800010807558-ffff800010807ecc: mv_xor_channel_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mv_xor_chan *mv_xor_channel_add(struct mv_xor_device *xordev, struct platform_device *pdev, int idx, dma_cap_mask_t cap_mask, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/mv_xor.c (c09256b8)
Location: drivers/dma/mv_xor.c:1034
Inline: False
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
```
**Symbols:**

```
c09256b8-c0925d2c: mv_xor_channel_add (STB_LOCAL)
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
