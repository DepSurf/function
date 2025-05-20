# Function: <code>mmci_dma_error</code>

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
void mmci_dma_error(struct mmci_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/host/mmci.c (ffff800010b476f0)
Location: drivers/mmc/host/mmci.c:542
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_data_irq
  - drivers/mmc/host/mmci.c:mmci_dmae_finalize
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_data_irq
  - drivers/mmc/host/mmci.c:mmci_dmae_finalize
```
**Symbols:**

```
ffff800010b457f8-ffff800010b45834: mmci_dma_error.part.0 (STB_LOCAL)
ffff800010b47a60-ffff800010b47a94: mmci_dma_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmci_dma_error(struct mmci_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/host/mmci.c (c0c20e80)
Location: drivers/mmc/host/mmci.c:542
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_data_irq
  - drivers/mmc/host/mmci.c:mmci_dmae_finalize
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_data_irq
  - drivers/mmc/host/mmci.c:mmci_dmae_finalize
```
**Symbols:**

```
c0c1f6e4-c0c1f718: mmci_dma_error.part.0 (STB_LOCAL)
c0c2116c-c0c21194: mmci_dma_error (STB_GLOBAL)
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
