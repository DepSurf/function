# Function: <code>i8042_controller_selftest</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816656d0)
Location: drivers/input/serio/i8042.c:888
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff816656d0-ffffffff8166578c: i8042_controller_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c5930)
Location: drivers/input/serio/i8042.c:888
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff816c5930-ffffffff816c59f3: i8042_controller_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f3950)
Location: drivers/input/serio/i8042.c:918
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff816f3950-ffffffff816f3a13: i8042_controller_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817092f0)
Location: drivers/input/serio/i8042.c:926
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff817092f0-ffffffff817093b3: i8042_controller_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff8177a4a0)
Location: drivers/input/serio/i8042.c:926
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff8177a4a0-ffffffff8177a563: i8042_controller_selftest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:926
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff817bace0-ffffffff817bad72: i8042_controller_selftest (STB_LOCAL)
ffffffff817bb907-ffffffff817bb951: i8042_controller_selftest.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:929
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff817e2150-ffffffff817e21e2: i8042_controller_selftest (STB_LOCAL)
ffffffff817e2d62-ffffffff817e2dac: i8042_controller_selftest.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:922
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81822bf0-ffffffff81822c77: i8042_controller_selftest (STB_LOCAL)
ffffffff81823790-ffffffff818237de: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:936
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81854080-ffffffff81854113: i8042_controller_selftest (STB_LOCAL)
ffffffff81854c50-ffffffff81854c9a: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:938
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff819262c0-ffffffff81926353: i8042_controller_selftest (STB_LOCAL)
ffffffff819270f5-ffffffff8192713f: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:961
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff8192de40-ffffffff8192ded3: i8042_controller_selftest (STB_LOCAL)
ffffffff81c22fbc-ffffffff81c23006: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:961
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81911230-ffffffff819112c3: i8042_controller_selftest (STB_LOCAL)
ffffffff81c150e5-ffffffff81c1512f: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:965
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff819b2900-ffffffff819b29ad: i8042_controller_selftest (STB_LOCAL)
ffffffff81d22bc5-ffffffff81d22c25: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:965
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81b11520-ffffffff81b1162b: i8042_controller_selftest (STB_LOCAL)
ffffffff81eee6fc-ffffffff81eee75f: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:965
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81ca1fe0-ffffffff81ca211c: i8042_controller_selftest (STB_LOCAL)
ffffffff820a62f9-ffffffff820a6329: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:965
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81d096a0-ffffffff81d097dc: i8042_controller_selftest (STB_LOCAL)
ffffffff82127700-ffffffff82127730: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:965
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81dbf330-ffffffff81dbf46c: i8042_controller_selftest (STB_LOCAL)
ffffffff82209081-ffffffff822090b1: i8042_controller_selftest.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b71500)
Location: drivers/input/serio/i8042.c:936
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
c000000000b71500-c000000000b71640: i8042_controller_selftest (STB_LOCAL)
```
</details>
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
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:936
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_pm_restore
```
**Symbols:**

```
ffffffff818091d0-ffffffff81809263: i8042_controller_selftest (STB_LOCAL)
ffffffff81809c60-ffffffff81809caa: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:936
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff817d0840-ffffffff817d08d3: i8042_controller_selftest (STB_LOCAL)
ffffffff817d1400-ffffffff817d144a: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:936
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81848210-ffffffff818482a3: i8042_controller_selftest (STB_LOCAL)
ffffffff81848de0-ffffffff81848e2a: i8042_controller_selftest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i8042_controller_selftest();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:936
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_controller_reset
```
**Symbols:**

```
ffffffff81863490-ffffffff81863523: i8042_controller_selftest (STB_LOCAL)
ffffffff81864000-ffffffff8186404a: i8042_controller_selftest.cold (STB_LOCAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
