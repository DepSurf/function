# Function: <code>sdhci_writeb</code>

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
In drivers/mmc/host/sdhci.c (c0c2688c)
Location: drivers/mmc/host/sdhci.h:669
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_cqe_enable
  - drivers/mmc/host/sdhci.c:sdhci_resume_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_bus_width
  - drivers/mmc/host/sdhci.c:sdhci_set_power
  - drivers/mmc/host/sdhci.c:sdhci_set_power
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
  - drivers/mmc/host/sdhci.c:sdhci_led_control
  - drivers/mmc/host/sdhci.c:sdhci_led_control
  - drivers/mmc/host/sdhci.c:sdhci_reset
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
