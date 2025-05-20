# Function: <code>mmc_vddrange_to_ocrmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816be860)
Location: drivers/mmc/core/core.c:1181
Inline: True
```
**Symbols:**

```
ffffffff816be860-ffffffff816be914: mmc_vddrange_to_ocrmask.part.12 (STB_LOCAL)
ffffffff816be920-ffffffff816be937: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81721210)
Location: drivers/mmc/core/core.c:1192
Inline: True
```
**Symbols:**

```
ffffffff81721210-ffffffff817212c3: mmc_vddrange_to_ocrmask.part.14 (STB_LOCAL)
ffffffff817212d0-ffffffff817212e7: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81753a90)
Location: drivers/mmc/core/core.c:1264
Inline: True
```
**Symbols:**

```
ffffffff81753a90-ffffffff81753b43: mmc_vddrange_to_ocrmask.part.17 (STB_LOCAL)
ffffffff81753b50-ffffffff81753b67: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81771770)
Location: drivers/mmc/core/core.c:1096
Inline: True
```
**Symbols:**

```
ffffffff81771770-ffffffff81771815: mmc_vddrange_to_ocrmask.part.19 (STB_LOCAL)
ffffffff81771820-ffffffff81771837: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e7680)
Location: drivers/mmc/core/core.c:1290
Inline: True
```
**Symbols:**

```
ffffffff817e7680-ffffffff817e7725: mmc_vddrange_to_ocrmask.part.22 (STB_LOCAL)
ffffffff817e7730-ffffffff817e7747: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81830540)
Location: drivers/mmc/core/core.c:1089
Inline: True
```
**Symbols:**

```
ffffffff81830540-ffffffff818305fc: mmc_vddrange_to_ocrmask.part.21 (STB_LOCAL)
ffffffff81830600-ffffffff81830617: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185c660)
Location: drivers/mmc/core/core.c:1092
Inline: True
```
**Symbols:**

```
ffffffff8185c660-ffffffff8185c71c: mmc_vddrange_to_ocrmask.part.21 (STB_LOCAL)
ffffffff8185c720-ffffffff8185c737: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a2990)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff818a2990-ffffffff818a2a5f: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d4c90)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff818d4c90-ffffffff818d4d49: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a72b0)
Location: drivers/mmc/core/core.c:1046
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff819a72b0-ffffffff819a7369: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819aa500)
Location: drivers/mmc/core/core.c:1046
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff819aa500-ffffffff819aa5b9: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198eda0)
Location: drivers/mmc/core/core.c:1052
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff8198eda0-ffffffff8198ee5b: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3a490)
Location: drivers/mmc/core/core.c:1053
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81a3a490-ffffffff81a3a54b: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba7280)
Location: drivers/mmc/core/core.c:1053
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81ba7280-ffffffff81ba7348: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d49890)
Location: drivers/mmc/core/core.c:1054
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81d49890-ffffffff81d49958: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db4110)
Location: drivers/mmc/core/core.c:1054
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81db4110-ffffffff81db41d8: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6c4e0)
Location: drivers/mmc/core/core.c:1059
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81e6c4e0-ffffffff81e6c5a8: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2e330)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffff800010b2e330-ffff800010b2e414: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0988c)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
c0c0988c-c0c09960: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c279c0)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
c000000000c279c0-c000000000c27ac8: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000707c42)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_of_parse_voltage
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffe000707c42-ffffffe000707ce4: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81878650)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff81878650-ffffffff81878709: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c9af0)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff818c9af0-ffffffff818c9ba9: mmc_vddrange_to_ocrmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 mmc_vddrange_to_ocrmask(int vdd_min, int vdd_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e6610)
Location: drivers/mmc/core/core.c:1063
Inline: False
Direct callers:
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
  - drivers/mmc/core/regulator.c:mmc_regulator_get_supply
```
**Symbols:**

```
ffffffff818e6610-ffffffff818e66c9: mmc_vddrange_to_ocrmask (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
