# Function: <code>mmci_dma_finalize</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmci_dma_finalize(struct mmci_host *host, struct mmc_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/host/mmci.c (ffff800010b46cb4)
Location: drivers/mmc/host/mmci.c:533
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_data_irq
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_data_irq
```
**Symbols:**

```
ffff800010b457b0-ffff800010b457f4: mmci_dma_finalize.part.0 (STB_LOCAL)
ffff800010b47a20-ffff800010b47a5c: mmci_dma_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmci_dma_finalize(struct mmci_host *host, struct mmc_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/host/mmci.c (c0c1fbec)
Location: drivers/mmc/host/mmci.c:533
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_data_irq
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_data_irq
```
**Symbols:**

```
c0c1f6b0-c0c1f6e4: mmci_dma_finalize.part.0 (STB_LOCAL)
c0c21144-c0c2116c: mmci_dma_finalize (STB_GLOBAL)
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
