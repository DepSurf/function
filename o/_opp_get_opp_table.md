# Function: <code>_opp_get_opp_table</code>

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
In drivers/opp/core.c (ffffffff81849b10)
Location: drivers/opp/core.c:880
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_genpd_virt_dev
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff81849b10-ffffffff81849c75: _opp_get_opp_table.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8188c8c0)
Location: drivers/opp/core.c:954
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff8188c8c0-ffffffff8188ca3d: _opp_get_opp_table.isra.0 (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff818bea30)
Location: drivers/opp/core.c:1003
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff818bea30-ffffffff818bebb6: _opp_get_opp_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81990ce5)
Location: drivers/opp/core.c:1086
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct opp_table *_opp_get_opp_table(struct device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19b68)
Location: drivers/opp/core.c:1003
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffff800010b19b68-ffff800010b19d30: _opp_get_opp_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct opp_table *_opp_get_opp_table(struct device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4824)
Location: drivers/opp/core.c:1003
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
c0bf4824-c0bf49f8: _opp_get_opp_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct opp_table *_opp_get_opp_table(struct device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0b650)
Location: drivers/opp/core.c:1003
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
c000000000c0b650-c000000000c0b83c: _opp_get_opp_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct opp_table *_opp_get_opp_table(struct device *dev, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000702436)
Location: drivers/opp/core.c:1003
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffe000702436-ffffffe0007025e8: _opp_get_opp_table (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff81863150)
Location: drivers/opp/core.c:1003
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff81863150-ffffffff818632d6: _opp_get_opp_table.isra.0 (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff8182be00)
Location: drivers/opp/core.c:1003
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff8182be00-ffffffff8182bf86: _opp_get_opp_table.isra.0 (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff818b3ee0)
Location: drivers/opp/core.c:1003
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff818b3ee0-ffffffff818b4066: _opp_get_opp_table.isra.0 (STB_LOCAL)
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
In drivers/opp/core.c (ffffffff818d0190)
Location: drivers/opp/core.c:1003
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
  - drivers/opp/core.c:dev_pm_opp_get_opp_table_indexed
```
**Symbols:**

```
ffffffff818d0190-ffffffff818d0316: _opp_get_opp_table.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
