# Function: <code>_mmci_dmae_prep_data</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int _mmci_dmae_prep_data(struct mmci_host *host, struct mmc_data *data, struct dma_chan **dma_chan, struct dma_async_tx_descriptor **dma_desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmci.c (ffff800010b45838)
Location: drivers/mmc/host/mmci.c:788
Inline: False
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:mmci_dmae_prep_data
```
**Symbols:**

```
ffff800010b45838-ffff800010b45a28: _mmci_dmae_prep_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _mmci_dmae_prep_data(struct mmci_host *host, struct mmc_data *data, struct dma_chan **dma_chan, struct dma_async_tx_descriptor **dma_desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/mmci.c (c0c1f718)
Location: drivers/mmc/host/mmci.c:788
Inline: False
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_dmae_prep_data
  - drivers/mmc/host/mmci.c:mmci_dmae_prep_data
```
**Symbols:**

```
c0c1f718-c0c1f94c: _mmci_dmae_prep_data (STB_LOCAL)
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
