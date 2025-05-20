# Function: <code>gpmc_cs_write_reg</code>

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
void gpmc_cs_write_reg(int cs, int idx, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/memory/omap-gpmc.c (c0c718c0)
Location: drivers/memory/omap-gpmc.c:265
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:omap3_gpmc_restore_context
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_probe_generic_child
  - drivers/memory/omap-gpmc.c:gpmc_cs_program_settings
  - drivers/memory/omap-gpmc.c:gpmc_cs_free
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
  - drivers/memory/omap-gpmc.c:gpmc_cs_request
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_memconf
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:set_gpmc_timing_reg
```
**Symbols:**

```
c0c6f898-c0c6f8d0: gpmc_cs_write_reg (STB_GLOBAL)
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
