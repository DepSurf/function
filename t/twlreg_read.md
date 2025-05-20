# Function: <code>twlreg_read</code>

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
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/regulator/twl-regulator.c (c0956fc8)
Location: drivers/regulator/twl-regulator.c:76
Inline: True
Inline callers:
  - drivers/regulator/twl-regulator.c:twl4030smps_get_voltage
  - drivers/regulator/twl-regulator.c:twl4030ldo_get_voltage_sel
  - drivers/regulator/twl-regulator.c:twlreg_grp
```
```
In drivers/regulator/twl6030-regulator.c (c0957bec)
Location: drivers/regulator/twl6030-regulator.c:87
Inline: True
Inline callers:
  - drivers/regulator/twl6030-regulator.c:twl6030smps_get_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030ldo_get_voltage_sel
  - drivers/regulator/twl6030-regulator.c:twl6030reg_get_status
  - drivers/regulator/twl6030-regulator.c:twl6030reg_is_enabled
  - drivers/regulator/twl6030-regulator.c:twlreg_grp
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
