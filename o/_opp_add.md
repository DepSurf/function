# Function: <code>_opp_add</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d5700)
Location: drivers/opp/core.c:1019
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff817d5700-ffffffff817d591c: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1063
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff8181e9c5-ffffffff8181ea0c: _opp_add.cold.22 (STB_LOCAL)
ffffffff8181e410-ffffffff8181e5c5: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1209
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff8184a820-ffffffff8184a863: _opp_add.cold.27 (STB_LOCAL)
ffffffff8184a210-ffffffff8184a3c5: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1283
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff8188d914-ffffffff8188d9ca: _opp_add.cold (STB_LOCAL)
ffffffff8188d080-ffffffff8188d1a9: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff818bfac0-ffffffff818bfb76: _opp_add.cold (STB_LOCAL)
ffffffff818bf2c0-ffffffff818bf3e9: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1439
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff819917f4-ffffffff81991837: _opp_add.cold (STB_LOCAL)
ffffffff81990ac0-ffffffff81990bee: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1523
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff81c295a5-ffffffff81c295e8: _opp_add.cold (STB_LOCAL)
ffffffff81994860-ffffffff8199498e: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1695
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff81c1b8ad-ffffffff81c1b96b: _opp_add.cold (STB_LOCAL)
ffffffff81979780-ffffffff819798c0: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1705
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff81d2bb4a-ffffffff81d2bc75: _opp_add.cold (STB_LOCAL)
ffffffff81a22790-ffffffff81a228d0: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1849
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff81ef7d63-ffffffff81ef7e8d: _opp_add.cold (STB_LOCAL)
ffffffff81b8b840-ffffffff81b8b984: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1872
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff820a8c01-ffffffff820a8c47: _opp_add.cold (STB_LOCAL)
ffffffff81d2aeb0-ffffffff81d2b0ea: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1880
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff82129df0-ffffffff82129e38: _opp_add.cold (STB_LOCAL)
ffffffff81d94130-ffffffff81d9436f: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1992
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff8220bb87-ffffffff8220bbcf: _opp_add.cold (STB_LOCAL)
ffffffff81e4bc50-ffffffff81e4be8f: _opp_add (STB_GLOBAL)
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
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1a5d0)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffff800010b1a5d0-ffff800010b1a7b4: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf5178)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
c0bf5178-c0bf5358: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0c320)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
c000000000c0c320-c000000000c0c580: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702cf8)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffe000702cf8-ffffffe000702e96: _opp_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff818641e0-ffffffff81864296: _opp_add.cold (STB_LOCAL)
ffffffff818639e0-ffffffff81863b09: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff8182ce90-ffffffff8182cf46: _opp_add.cold (STB_LOCAL)
ffffffff8182c690-ffffffff8182c7b9: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff818b4f70-ffffffff818b5026: _opp_add.cold (STB_LOCAL)
ffffffff818b4770-ffffffff818b4899: _opp_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _opp_add(struct device *dev, struct dev_pm_opp *new_opp, struct opp_table *opp_table, bool rate_not_available);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1332
Inline: False
Direct callers:
  - drivers/opp/core.c:_opp_add_v1
```
**Symbols:**

```
ffffffff818d1220-ffffffff818d12d6: _opp_add.cold (STB_LOCAL)
ffffffff818d0a20-ffffffff818d0b49: _opp_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rate_not_available</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool rate_not_available</code>
</li>
</ul>
</details>
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
