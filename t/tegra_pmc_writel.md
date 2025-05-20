# Function: <code>tegra_pmc_writel</code>

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
void tegra_pmc_writel(struct tegra_pmc *pmc, u32 value, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/soc/tegra/pmc.c (c093bb04)
Location: drivers/soc/tegra/pmc.c:382
Inline: True
Direct callers:
  - drivers/soc/tegra/pmc.c:tegra20_pmc_setup_irq_polarity
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra20_pmc_init
  - drivers/soc/tegra/pmc.c:tegra_pmc_resume
  - drivers/soc/tegra/pmc.c:tegra_pmc_suspend
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_set
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/soc/tegra/pmc.c:tegra_io_pad_power_disable
  - drivers/soc/tegra/pmc.c:tegra_io_pad_power_disable
  - drivers/soc/tegra/pmc.c:tegra_io_pad_power_enable
  - drivers/soc/tegra/pmc.c:tegra_io_pad_power_enable
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:tegra_pmc_restart_notify
  - drivers/soc/tegra/pmc.c:__tegra_powergate_remove_clamping
  - drivers/soc/tegra/pmc.c:__tegra_powergate_remove_clamping
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
```
**Symbols:**

```
c093bb04-c093bc00: tegra_pmc_writel (STB_LOCAL)
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
