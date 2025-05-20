# Function: <code>sdhci_do_reset</code>

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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sdhci_do_reset(struct sdhci_host *host, u8 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/sdhci.c (c0c22724)
Location: drivers/mmc/host/sdhci.c:231
Inline: True
Direct callers:
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/mmc/host/sdhci.c:__sdhci_read_caps
  - drivers/mmc/host/sdhci.c:sdhci_cqe_disable
  - drivers/mmc/host/sdhci.c:sdhci_cqe_disable
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_card_event
  - drivers/mmc/host/sdhci.c:sdhci_card_event
  - drivers/mmc/host/sdhci.c:sdhci_abort_tuning
  - drivers/mmc/host/sdhci.c:sdhci_abort_tuning
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_finish_data
  - drivers/mmc/host/sdhci.c:sdhci_finish_data
  - drivers/mmc/host/sdhci.c:sdhci_init
  - drivers/mmc/host/sdhci.c:sdhci_init
```
**Symbols:**

```
c0c22724-c0c227b0: sdhci_do_reset (STB_LOCAL)
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
