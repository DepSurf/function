# Function: <code>tegra_bpmp_transfer</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
int tegra_bpmp_transfer(struct tegra_bpmp *bpmp, struct tegra_bpmp_message *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/tegra/bpmp.c (c0c41914)
Location: drivers/firmware/tegra/bpmp.c:354
Inline: False
Direct callers:
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_clk_transfer
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_powergate_set_state
  - drivers/reset/tegra/reset-bpmp.c:tegra_bpmp_reset_common
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_mrq_is_supported
  - drivers/firmware/tegra/bpmp-debugfs.c:tegra_bpmp_init_debugfs
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_store
  - drivers/firmware/tegra/bpmp-debugfs.c:debugfs_show
```
**Symbols:**

```
c0c41914-c0c41bd4: tegra_bpmp_transfer (STB_GLOBAL)
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
