# Function: <code>_opp_remove_all_static</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8184a0f0)
Location: drivers/opp/core.c:952
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffff8184a0f0-ffffffff8184a149: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188cf60)
Location: drivers/opp/core.c:1026
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffff8188cf60-ffffffff8188cfb6: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf1a0)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffff818bf1a0-ffffffff818bf1f6: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819908e0)
Location: drivers/opp/core.c:1268
Inline: False
Direct callers:
  - drivers/opp/core.c:_dev_pm_opp_find_and_remove_table
```
**Symbols:**

```
ffffffff819908e0-ffffffff819909e3: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81992cc9)
Location: drivers/opp/core.c:1371
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff81994720-ffffffff8199478f: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819775b9)
Location: drivers/opp/core.c:1528
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff81978d60-ffffffff81978dcf: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a1ff09)
Location: drivers/opp/core.c:1538
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff81a21ce0-ffffffff81a21d4f: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b88ac7)
Location: drivers/opp/core.c:1682
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff81b8ad80-ffffffff81b8adef: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28847)
Location: drivers/opp/core.c:1658
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff81d2a2f0-ffffffff81d2a35f: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d919e5)
Location: drivers/opp/core.c:1666
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff81d934e0-ffffffff81d9354f: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e49315)
Location: drivers/opp/core.c:1776
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff81e4af30-ffffffff81e4af9f: _opp_remove_all_static (STB_GLOBAL)
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
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a448)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffff800010b1a448-ffff800010b1a4bc: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf5040)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
c0bf5040-c0bf50b0: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0c120)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
c000000000c0c120-c000000000c0c1c8: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702ba8)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffe000702ba8-ffffffe000702c04: _opp_remove_all_static (STB_GLOBAL)
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
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818638c0)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffff818638c0-ffffffff81863916: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182c570)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffff8182c570-ffffffff8182c5c6: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4650)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffff818b4650-ffffffff818b46a6: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _opp_remove_all_static(struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0900)
Location: drivers/opp/core.c:1075
Inline: False
Direct callers:
  - drivers/opp/core.c:_put_opp_list_kref
```
**Symbols:**

```
ffffffff818d0900-ffffffff818d0956: _opp_remove_all_static (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
