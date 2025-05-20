# Function: <code>sdhci_writel</code>

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
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void sdhci_writel(struct sdhci_host *host, u32 val, int reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/sdhci.c (c0c25430)
Location: drivers/mmc/host/sdhci.h:653
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_runtime_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_runtime_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_end_tuning
  - drivers/mmc/host/sdhci.c:sdhci_end_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_tuning
  - drivers/mmc/host/sdhci.c:sdhci_start_tuning
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_send_command
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_set_sdma_addr
  - drivers/mmc/host/sdhci.c:sdhci_set_default_irqs
  - drivers/mmc/host/sdhci.c:sdhci_set_default_irqs
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2f30c)
Location: drivers/mmc/host/sdhci.h:653
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_reset
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_reset
```
**Symbols:**

```
c0c22024-c0c2206c: sdhci_writel (STB_LOCAL)
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
