# Function: <code>mmc_get_dma_dir</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmci.c (ffff800010b458dc)
Location: include/linux/mmc/host.h:588
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (ffff800010b483d0)
Location: include/linux/mmc/host.h:588
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
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
In drivers/mmc/host/mmci.c (c0c1f7f0)
Location: include/linux/mmc/host.h:588
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:_mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:mmci_dma_unmap
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c2192c)
Location: include/linux/mmc/host.h:588
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_unprep_data
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_prep_data
```
```
In drivers/mmc/host/sdhci.c (c0c22c68)
Location: include/linux/mmc/host.h:588
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_post_req
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
  - drivers/mmc/host/sdhci.c:sdhci_pre_dma_transfer
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c300)
Location: include/linux/mmc/host.h:588
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_post_req
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_pre_dma_transfer
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_dma_callback
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a61e)
Location: include/linux/mmc/host.h:588
Inline: True
```
</details>
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
