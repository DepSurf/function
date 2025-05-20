# Function: <code>dev_pm_opp_get</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4e48)
Location: drivers/opp/core.c:916
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181dbf8)
Location: drivers/opp/core.c:923
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff8181e390-ffffffff8181e3a5: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818498e8)
Location: drivers/opp/core.c:1022
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff8184a1a0-ffffffff8184a1b5: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188c6f5)
Location: drivers/opp/core.c:1096
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff8188d010-ffffffff8188d025: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818be865)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff818bf250-ffffffff818bf265: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81990f9f)
Location: drivers/opp/core.c:1208
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81990890-ffffffff819908d2: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8199318f)
Location: drivers/opp/core.c:1277
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff819946d0-ffffffff81994712: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81977a7f)
Location: drivers/opp/core.c:1434
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81978d10-ffffffff81978d52: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a2097f)
Location: drivers/opp/core.c:1444
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81a21c90-ffffffff81a21cd2: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b895c3)
Location: drivers/opp/core.c:1589
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81b8ad10-ffffffff81b8ad7c: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28dd3)
Location: drivers/opp/core.c:1561
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
```
**Symbols:**

```
ffffffff81d2a270-ffffffff81d2a2dc: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91f73)
Location: drivers/opp/core.c:1569
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
```
**Symbols:**

```
ffffffff81d93460-ffffffff81d934cc: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e498a3)
Location: drivers/opp/core.c:1679
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_adjust_voltage
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_xlate_required_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_opp_table_find_key
```
**Symbols:**

```
ffffffff81e4aeb0-ffffffff81e4af1c: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1993c)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
Direct callers:
  - drivers/opp/of.c:_find_opp_of_np
```
**Symbols:**

```
ffff800010b1a548-ffff800010b1a574: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4660)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
Direct callers:
  - drivers/opp/of.c:_find_opp_of_np
```
**Symbols:**

```
c0bf5110-c0bf5130: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0b3c8)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
Direct callers:
  - drivers/opp/of.c:_find_opp_of_np
```
**Symbols:**

```
c000000000c0c290-c000000000c0c2b0: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702238)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
Direct callers:
  - drivers/opp/of.c:_find_opp_of_np
```
**Symbols:**

```
ffffffe000702c7e-ffffffe000702ca8: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81862f85)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81863970-ffffffff81863985: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182bc35)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff8182c620-ffffffff8182c635: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3d15)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff818b4700-ffffffff818b4715: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cffc5)
Location: drivers/opp/core.c:1145
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_set_availability
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff818d09b0-ffffffff818d09c5: dev_pm_opp_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
