# Function: <code>mmc_priv</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmci.c (ffff800010b44cd4)
Location: include/linux/mmc/host.h:478
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_request
  - drivers/mmc/host/mmci.c:mmci_post_request
  - drivers/mmc/host/mmci.c:mmci_pre_request
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
In drivers/mmc/host/mmci.c (c0c1e874)
Location: include/linux/mmc/host.h:478
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_request
  - drivers/mmc/host/mmci.c:mmci_post_request
  - drivers/mmc/host/mmci.c:mmci_pre_request
```
```
In drivers/mmc/host/sdhci.c (c0c22380)
Location: include/linux/mmc/host.h:478
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_alloc_host
  - drivers/mmc/host/sdhci.c:sdhci_cqe_disable
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_card_event
  - drivers/mmc/host/sdhci.c:sdhci_pre_req
  - drivers/mmc/host/sdhci.c:sdhci_execute_tuning
  - drivers/mmc/host/sdhci.c:sdhci_card_busy
  - drivers/mmc/host/sdhci.c:sdhci_start_signal_voltage_switch
  - drivers/mmc/host/sdhci.c:sdhci_ack_sdio_irq
  - drivers/mmc/host/sdhci.c:sdhci_hw_reset
  - drivers/mmc/host/sdhci.c:sdhci_get_ro
  - drivers/mmc/host/sdhci.c:sdhci_get_cd
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_request
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b13c)
Location: include/linux/mmc/host.h:478
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_request
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_pre_req
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2d9f4)
Location: include/linux/mmc/host.h:478
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_sdhci_dumpregs
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
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
In drivers/mmc/host/mmc_spi.c (ffffffe00071a284)
Location: include/linux/mmc/host.h:478
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_set_ios
  - drivers/mmc/host/mmc_spi.c:mmc_spi_request
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
