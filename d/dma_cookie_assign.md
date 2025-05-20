# Function: <code>dma_cookie_assign</code>

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
In drivers/dma/virt-dma.c (ffffffff81706abc)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
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
In drivers/dma/virt-dma.c (ffffffff8178237c)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
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
In drivers/dma/virt-dma.c (ffffffff818b8d9c)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
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
In drivers/dma/virt-dma.c (ffffffff81a0641c)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
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
In drivers/dma/virt-dma.c (ffffffff81a4f2ac)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
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
In drivers/dma/virt-dma.c (ffffffff81a9af4c)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
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
In drivers/dma/virt-dma.c (ffff8000107fe5b8)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/mv_xor.c (ffff8000108070c8)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808ba4)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_tx_submit
```
```
In drivers/dma/mxs-dma.c (ffff8000108096cc)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_tx_submit
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080ba88)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
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
In drivers/dma/virt-dma.c (c091f6cc)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/mv_xor.c (c092400c)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
```
```
In drivers/dma/mxs-dma.c (c0926164)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_tx_submit
```
```
In drivers/dma/ipu/ipu_idmac.c (c0928394)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
```
```
In drivers/dma/tegra20-apb-dma.c (c092987c)
Location: drivers/dma/dmaengine.h:29
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_tx_submit
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
