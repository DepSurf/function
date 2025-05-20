# Function: <code>i8042_dritek_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81665360)
Location: drivers/input/serio/i8042.c:1095
Inline: False
```
**Symbols:**

```
ffffffff81665360-ffffffff816653b8: i8042_dritek_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c55c0)
Location: drivers/input/serio/i8042.c:1095
Inline: False
```
**Symbols:**

```
ffffffff816c55c0-ffffffff816c5618: i8042_dritek_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f35e0)
Location: drivers/input/serio/i8042.c:1127
Inline: False
```
**Symbols:**

```
ffffffff816f35e0-ffffffff816f3638: i8042_dritek_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81708f80)
Location: drivers/input/serio/i8042.c:1135
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff81708f80-ffffffff81708fd8: i8042_dritek_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8177a130)
Location: drivers/input/serio/i8042.c:1135
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff8177a130-ffffffff8177a188: i8042_dritek_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1135
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff817baac0-ffffffff817bab0c: i8042_dritek_enable (STB_LOCAL)
ffffffff817bb8cc-ffffffff817bb8df: i8042_dritek_enable.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1138
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff817e1f30-ffffffff817e1f7c: i8042_dritek_enable (STB_LOCAL)
ffffffff817e2d27-ffffffff817e2d3a: i8042_dritek_enable.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1131
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff818228e0-ffffffff8182292c: i8042_dritek_enable (STB_LOCAL)
ffffffff81823703-ffffffff81823716: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1148
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff81853d70-ffffffff81853dbc: i8042_dritek_enable (STB_LOCAL)
ffffffff81854bc3-ffffffff81854bd6: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81926ac5)
Location: drivers/input/serio/i8042.c:1150
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff81926020-ffffffff8192606c: i8042_dritek_enable (STB_LOCAL)
ffffffff81926f0f-ffffffff81926f22: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8192e635)
Location: drivers/input/serio/i8042.c:1173
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff8192dba0-ffffffff8192dbec: i8042_dritek_enable (STB_LOCAL)
ffffffff81c22dd6-ffffffff81c22de9: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81911a10)
Location: drivers/input/serio/i8042.c:1173
Inline: True
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
```
**Symbols:**

```
ffffffff81910f90-ffffffff81910fdc: i8042_dritek_enable (STB_LOCAL)
ffffffff81c15058-ffffffff81c1506b: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff819b322f)
Location: drivers/input/serio/i8042.c:1177
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81b12317)
Location: drivers/input/serio/i8042.c:1177
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81ca2d61)
Location: drivers/input/serio/i8042.c:1177
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81d0a421)
Location: drivers/input/serio/i8042.c:1177
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81dc00b1)
Location: drivers/input/serio/i8042.c:1177
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1148
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_pm_restore
```
**Symbols:**

```
ffffffff81808ec0-ffffffff81808f0c: i8042_dritek_enable (STB_LOCAL)
ffffffff81809bd3-ffffffff81809be6: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1148
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff817d0530-ffffffff817d057c: i8042_dritek_enable (STB_LOCAL)
ffffffff817d1373-ffffffff817d1386: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1148
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff81847f00-ffffffff81847f4c: i8042_dritek_enable (STB_LOCAL)
ffffffff81848d53-ffffffff81848d66: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void i8042_dritek_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:1148
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
```
**Symbols:**

```
ffffffff81863180-ffffffff818631cc: i8042_dritek_enable (STB_LOCAL)
ffffffff81863f73-ffffffff81863f86: i8042_dritek_enable.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
