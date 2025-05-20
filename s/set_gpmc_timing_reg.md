# Function: <code>set_gpmc_timing_reg</code>

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
int set_gpmc_timing_reg(int cs, int reg, int st_bit, int end_bit, int max, int time, enum gpmc_clk_domain cd, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/memory/omap-gpmc.c (c0c6f198)
Location: drivers/memory/omap-gpmc.c:603
Inline: False
Direct callers:
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
```
**Symbols:**

```
c0c6f198-c0c6f2e4: set_gpmc_timing_reg (STB_LOCAL)
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
