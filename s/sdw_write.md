# Function: <code>sdw_write</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sdw_write(struct sdw_slave *slave, u32 addr, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/soundwire/bus.c (ffffffff818c1de0)
Location: drivers/soundwire/bus.c:392
Inline: True
Inline callers:
  - drivers/soundwire/bus.c:sdw_handle_slave_status
  - drivers/soundwire/bus.c:sdw_handle_slave_status
  - drivers/soundwire/bus.c:sdw_handle_slave_status
  - drivers/soundwire/bus.c:sdw_handle_slave_alerts
  - drivers/soundwire/bus.c:sdw_configure_dpn_intr
Direct callers:
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_program_params
  - drivers/soundwire/stream.c:sdw_prep_deprep_ports
  - drivers/soundwire/stream.c:sdw_prep_deprep_ports
```
**Symbols:**

```
ffffffff818c1540-ffffffff818c1560: sdw_write (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
</ul>
