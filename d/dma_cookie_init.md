# Function: <code>dma_cookie_init</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81706c05)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff817824b5)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff818b8f15)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a065b5)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a4f445)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffffffff81a9b0e5)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma/virt-dma.c (ffff8000107fe4e4)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
```
In drivers/dma/mv_xor.c (0)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mv_xor_v2.c (ffff80001080916c)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff80001148efbc)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f614)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
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
In drivers/dma/virt-dma.c (c091f924)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_init
```
```
In drivers/dma/mv_xor.c (c0925914)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mxs-dma.c (c158e9d8)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (c158efc8)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
```
```
In drivers/dma/tegra20-apb-dma.c (c092a750)
Location: drivers/dma/dmaengine.h:16
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_alloc_chan_resources
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
