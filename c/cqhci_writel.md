# Function: <code>cqhci_writel</code>

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
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2e26c)
Location: drivers/mmc/host/cqhci.h:211
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:esdhc_cqe_enable
```
```
In drivers/mmc/host/cqhci.c (c0c31634)
Location: drivers/mmc/host/cqhci.h:211
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_recovery_finish
  - drivers/mmc/host/cqhci.c:cqhci_recovery_finish
  - drivers/mmc/host/cqhci.c:cqhci_recovery_finish
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_irq
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_off
  - drivers/mmc/host/cqhci.c:cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_disable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:__cqhci_enable
  - drivers/mmc/host/cqhci.c:cqhci_set_irqs
  - drivers/mmc/host/cqhci.c:cqhci_set_irqs
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
