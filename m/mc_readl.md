# Function: <code>mc_readl</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/memory/tegra/mc.c (c0c74000)
Location: drivers/memory/tegra/mc.h:24
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra20_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_irq
  - drivers/memory/tegra/mc.c:tegra_mc_get_emem_device_count
  - drivers/memory/tegra/mc.c:tegra_mc_reset_status_common
  - drivers/memory/tegra/mc.c:tegra_mc_unblock_dma_common
  - drivers/memory/tegra/mc.c:tegra_mc_dma_idling_common
  - drivers/memory/tegra/mc.c:tegra_mc_block_dma_common
```
```
In drivers/memory/tegra/tegra20.c (c0c747ec)
Location: drivers/memory/tegra/mc.h:24
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20.c:tegra20_mc_unblock_dma
  - drivers/memory/tegra/tegra20.c:tegra20_mc_reset_status
  - drivers/memory/tegra/tegra20.c:tegra20_mc_dma_idling
  - drivers/memory/tegra/tegra20.c:tegra20_mc_block_dma
  - drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_deassert
  - drivers/memory/tegra/tegra20.c:tegra20_mc_hotreset_assert
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
