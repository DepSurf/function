# Function: <code>_set_required_opps</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818489f0)
Location: drivers/opp/core.c:629
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818489f0-ffffffff81848b30: _set_required_opps.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:697
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8188b390-ffffffff8188b496: _set_required_opps (STB_LOCAL)
ffffffff8188d4be-ffffffff8188d524: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818bd470-ffffffff818bd576: _set_required_opps (STB_LOCAL)
ffffffff818bf71e-ffffffff818bf784: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:785
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8198db10-ffffffff8198dc16: _set_required_opps (STB_LOCAL)
ffffffff8199119e-ffffffff81991204: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, bool up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819916d0)
Location: drivers/opp/core.c:801
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff819916d0-ffffffff819917d1: _set_required_opps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, bool up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81975ca0)
Location: drivers/opp/core.c:885
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81975ca0-ffffffff81975db6: _set_required_opps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, bool up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:885
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81a1ea70-ffffffff81a1eba8: _set_required_opps (STB_LOCAL)
ffffffff81d2b0e9-ffffffff81d2b11d: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, bool up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1030
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81b87390-ffffffff81b8750d: _set_required_opps (STB_LOCAL)
ffffffff81ef7291-ffffffff81ef72c7: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, bool up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:957
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81d26c00-ffffffff81d26d96: _set_required_opps (STB_LOCAL)
ffffffff820a89a2-ffffffff820a89bf: _set_required_opps.cold (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff81d93761)
Location: drivers/opp/core.c:1000
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81e4bac0)
Location: drivers/opp/core.c:1065
Inline: True
Direct callers:
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81e4bac0-ffffffff81e4bb65: _set_required_opps.isra.0 (STB_LOCAL)
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
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b17f08)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffff800010b17f08-ffff800010b18088: _set_required_opps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf2f78)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
c0bf2f78-c0bf30c0: _set_required_opps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09620)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
c000000000c09620-c000000000c09840: _set_required_opps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000700d5e)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffe000700d5e-ffffffe000700e7e: _set_required_opps (STB_LOCAL)
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
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81861b90-ffffffff81861c96: _set_required_opps (STB_LOCAL)
ffffffff81863e3e-ffffffff81863ea4: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8182a840-ffffffff8182a946: _set_required_opps (STB_LOCAL)
ffffffff8182caee-ffffffff8182cb54: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818b2920-ffffffff818b2a26: _set_required_opps (STB_LOCAL)
ffffffff818b4bce-ffffffff818b4c34: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _set_required_opps(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:745
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff818cebd0-ffffffff818cecd6: _set_required_opps (STB_LOCAL)
ffffffff818d0e7e-ffffffff818d0ee4: _set_required_opps.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool up</code>
</li>
</ul>
</details>
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
