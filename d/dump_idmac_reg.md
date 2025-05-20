# Function: <code>dump_idmac_reg</code>

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
void dump_idmac_reg(struct ipu *ipu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080b938)
Location: drivers/dma/ipu/ipu_idmac.c:70
Inline: False
Direct callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
```
**Symbols:**

```
ffff80001080b938-ffff80001080ba00: dump_idmac_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dump_idmac_reg(struct ipu *ipu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/ipu/ipu_idmac.c (c0927c64)
Location: drivers/dma/ipu/ipu_idmac.c:70
Inline: True
Direct callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
  - drivers/dma/ipu/ipu_idmac.c:idmac_tx_submit
```
**Symbols:**

```
c0927c64-c0927d38: dump_idmac_reg (STB_LOCAL)
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
