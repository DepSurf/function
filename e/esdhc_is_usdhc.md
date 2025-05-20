# Function: <code>esdhc_is_usdhc</code>

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
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2f2a8)
Location: drivers/mmc/host/sdhci-esdhc-imx.c:292
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_timeout
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_get_max_timeout_count
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_set_uhs_signaling
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writeb_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writew_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readw_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_writel_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_readl_le
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
