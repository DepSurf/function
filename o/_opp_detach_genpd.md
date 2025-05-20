# Function: <code>_opp_detach_genpd</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188b940)
Location: drivers/opp/core.c:1754
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff8188b940-ffffffff8188b9a5: _opp_detach_genpd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818bda20)
Location: drivers/opp/core.c:1803
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff818bda20-ffffffff818bda85: _opp_detach_genpd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8198dd70)
Location: drivers/opp/core.c:1917
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff8198dd70-ffffffff8198dde7: _opp_detach_genpd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81991db3)
Location: drivers/opp/core.c:2014
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81991930-ffffffff819919a7: _opp_detach_genpd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81978cb1)
Location: drivers/opp/core.c:2299
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81975f40-ffffffff81975fb7: _opp_detach_genpd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81a21c31)
Location: drivers/opp/core.c:2309
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81a1ec90-ffffffff81a1ed07: _opp_detach_genpd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8ac72)
Location: drivers/opp/core.c:2449
Inline: True
Inline callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
Direct callers:
  - drivers/opp/core.c:devm_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81b875b0-ffffffff81b87633: _opp_detach_genpd.part.0 (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff81d278c8)
Location: drivers/opp/core.c:2403
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_clear_config
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
In drivers/opp/core.c (ffffffff81d90a68)
Location: drivers/opp/core.c:2411
Inline: True
Inline callers:
  - drivers/opp/core.c:_opp_clear_config
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
In drivers/opp/core.c (ffffffff81e4ac89)
Location: drivers/opp/core.c:2363
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_opp_clear_config
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffff800010b18848)
Location: drivers/opp/core.c:1803
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffff800010b18848-ffff800010b188c4: _opp_detach_genpd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3640)
Location: drivers/opp/core.c:1803
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
c0bf3640-c0bf36b4: _opp_detach_genpd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c09db0)
Location: drivers/opp/core.c:1803
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
c000000000c09db0-c000000000c09e60: _opp_detach_genpd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _opp_detach_genpd(struct opp_table *opp_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701272)
Location: drivers/opp/core.c:1803
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffe000701272-ffffffe0007012ea: _opp_detach_genpd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81862140)
Location: drivers/opp/core.c:1803
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff81862140-ffffffff818621a5: _opp_detach_genpd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8182adf0)
Location: drivers/opp/core.c:1803
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff8182adf0-ffffffff8182ae55: _opp_detach_genpd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818b2ed0)
Location: drivers/opp/core.c:1803
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff818b2ed0-ffffffff818b2f35: _opp_detach_genpd.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff818cf180)
Location: drivers/opp/core.c:1803
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_detach_genpd
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
```
**Symbols:**

```
ffffffff818cf180-ffffffff818cf1e5: _opp_detach_genpd.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
