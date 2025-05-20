# Function: <code>serdes_wr</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-xgene.c (ffff800010688458)
Location: drivers/phy/phy-xgene.c:657
Inline: True
Direct callers:
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_gen_avg_val
  - drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal
  - drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal
  - drivers/phy/phy-xgene.c:xgene_phy_force_lat_summer_cal
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:xgene_phy_sata_cfg_lanes
  - drivers/phy/phy-xgene.c:serdes_setbits
  - drivers/phy/phy-xgene.c:serdes_clrbits
```
**Symbols:**

```
ffff800010688458-ffff800010688514: serdes_wr.isra.0 (STB_LOCAL)
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
