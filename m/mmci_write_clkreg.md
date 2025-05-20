# Function: <code>mmci_write_clkreg</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void mmci_write_clkreg(struct mmci_host *host, u32 clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmci.c (ffff800010b45cfc)
Location: drivers/mmc/host/mmci.c:327
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
Direct callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_clkreg
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_clkreg
```
**Symbols:**

```
ffff800010b46e28-ffff800010b46e70: mmci_write_clkreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mmci_write_clkreg(struct mmci_host *host, u32 clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmci.c (c0c20450)
Location: drivers/mmc/host/mmci.c:327
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/mmci.c:mmci_start_data
Direct callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:mmci_sdmmc_set_clkreg
```
**Symbols:**

```
c0c20678-c0c206b8: mmci_write_clkreg (STB_GLOBAL)
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
