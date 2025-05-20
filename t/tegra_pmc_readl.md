# Function: <code>tegra_pmc_readl</code>

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
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/soc/tegra/pmc.c (c093bd60)
Location: drivers/soc/tegra/pmc.c:360
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra20_pmc_setup_irq_polarity
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:reset_level_show
  - drivers/soc/tegra/pmc.c:reset_reason_show
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:tegra_powergate_is_powered
  - drivers/soc/tegra/pmc.c:tegra_powergate_is_powered
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
Direct callers:
  - drivers/soc/tegra/pmc.c:tegra20_pmc_setup_irq_polarity
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:reset_level_show
  - drivers/soc/tegra/pmc.c:reset_reason_show
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:tegra_powergate_is_powered
  - drivers/soc/tegra/pmc.c:tegra_powergate_is_powered
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
```
**Symbols:**

```
c093b6a0-c093b774: tegra_pmc_readl.part.0 (STB_LOCAL)
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
