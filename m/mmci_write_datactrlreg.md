# Function: <code>mmci_write_datactrlreg</code>

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
In drivers/mmc/host/mmci.c (ffff800010b455a4)
Location: drivers/mmc/host/mmci.c:349
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_stop_data
  - drivers/mmc/host/mmci.c:mmci_dma_start
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmci_write_datactrlreg(struct mmci_host *host, u32 datactrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmci.c (c0c1e450)
Location: drivers/mmc/host/mmci.c:349
Inline: False
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_cmd_irq
  - drivers/mmc/host/mmci.c:mmci_data_irq
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_dma_start
```
**Symbols:**

```
c0c1e450-c0c1e49c: mmci_write_datactrlreg (STB_LOCAL)
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
