# Function: <code>twlreg_grp</code>

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
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int twlreg_grp(struct regulator_dev *rdev);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/twl-regulator.c (c0956ecc)
Location: drivers/regulator/twl-regulator.c:98
Inline: False
Direct callers:
  - drivers/regulator/twl-regulator.c:twl4030reg_get_status
  - drivers/regulator/twl-regulator.c:twl4030reg_disable
  - drivers/regulator/twl-regulator.c:twl4030reg_enable
  - drivers/regulator/twl-regulator.c:twl4030reg_is_enabled
```
```
In drivers/regulator/twl6030-regulator.c (c0957a9c)
Location: drivers/regulator/twl6030-regulator.c:106
Inline: False
Direct callers:
  - drivers/regulator/twl6030-regulator.c:twl6030reg_set_mode
  - drivers/regulator/twl6030-regulator.c:twl6030reg_get_status
  - drivers/regulator/twl6030-regulator.c:twl6030reg_enable
  - drivers/regulator/twl6030-regulator.c:twl6030reg_is_enabled
```
**Symbols:**

```
c0956ecc-c0956f3c: twlreg_grp (STB_LOCAL)
c0957a9c-c0957b0c: twlreg_grp (STB_LOCAL)
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
