# Function: <code>ipu_submit_buffer</code>

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
int ipu_submit_buffer(struct idmac_channel *ichan, struct idmac_tx_desc *desc, struct scatterlist *sg, int buf_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080b378)
Location: drivers/dma/ipu/ipu_idmac.c:773
Inline: False
Direct callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
```
**Symbols:**

```
ffff80001080b378-ffff80001080b5b8: ipu_submit_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipu_submit_buffer(struct idmac_channel *ichan, struct idmac_tx_desc *desc, struct scatterlist *sg, int buf_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/ipu/ipu_idmac.c (c0927aac)
Location: drivers/dma/ipu/ipu_idmac.c:773
Inline: False
Direct callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_interrupt
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
```
**Symbols:**

```
c0927aac-c0927c64: ipu_submit_buffer (STB_LOCAL)
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
