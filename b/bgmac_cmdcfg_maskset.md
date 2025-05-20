# Function: <code>bgmac_cmdcfg_maskset</code>

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
void bgmac_cmdcfg_maskset(struct bgmac *bgmac, u32 mask, u32 set, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e1f08)
Location: drivers/net/ethernet/broadcom/bgmac.c:749
Inline: False
Direct callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_init
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_chip_reset
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_mac_speed
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_rx_mode
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_rx_mode
```
**Symbols:**

```
ffff8000109e1f08-ffff8000109e2010: bgmac_cmdcfg_maskset (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
