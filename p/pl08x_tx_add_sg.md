# Function: <code>pl08x_tx_add_sg</code>

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
int pl08x_tx_add_sg(struct pl08x_txd *txd, enum dma_transfer_direction direction, dma_addr_t slave_addr, dma_addr_t buf_addr, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/amba-pl08x.c (ffff8000107ffcc8)
Location: drivers/dma/amba-pl08x.c:2023
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
```
**Symbols:**

```
ffff8000107ffcc8-ffff8000107ffd78: pl08x_tx_add_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pl08x_tx_add_sg(struct pl08x_txd *txd, enum dma_transfer_direction direction, dma_addr_t slave_addr, dma_addr_t buf_addr, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma/amba-pl08x.c (c0920768)
Location: drivers/dma/amba-pl08x.c:2023
Inline: False
Direct callers:
  - drivers/dma/amba-pl08x.c:pl08x_prep_dma_cyclic
  - drivers/dma/amba-pl08x.c:pl08x_prep_slave_sg
```
**Symbols:**

```
c0920768-c09207f8: pl08x_tx_add_sg (STB_LOCAL)
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
