# Function: <code>_add_opp_table_indexed</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct opp_table *_add_opp_table_indexed(struct device *dev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81994010)
Location: drivers/opp/core.c:1146
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81994010-ffffffff819940cb: _add_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct opp_table *_add_opp_table_indexed(struct device *dev, int index, bool getclk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1299
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81c1b565-ffffffff81c1b611: _add_opp_table_indexed.cold (STB_LOCAL)
ffffffff81978190-ffffffff81978378: _add_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct opp_table *_add_opp_table_indexed(struct device *dev, int index, bool getclk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1309
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81d2b736-ffffffff81d2b7f7: _add_opp_table_indexed.cold (STB_LOCAL)
ffffffff81a21100-ffffffff81a212f4: _add_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct opp_table *_add_opp_table_indexed(struct device *dev, int index, bool getclk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1454
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_attach_genpd
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_set_regulators
  - drivers/opp/core.c:dev_pm_opp_set_prop_name
  - drivers/opp/core.c:dev_pm_opp_set_supported_hw
```
**Symbols:**

```
ffffffff81ef7954-ffffffff81ef7a13: _add_opp_table_indexed.cold (STB_LOCAL)
ffffffff81b8a070-ffffffff81b8a267: _add_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct opp_table *_add_opp_table_indexed(struct device *dev, int index, bool getclk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1426
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_config
```
**Symbols:**

```
ffffffff820a8b61-ffffffff820a8b75: _add_opp_table_indexed.cold (STB_LOCAL)
ffffffff81d29710-ffffffff81d299ec: _add_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct opp_table *_add_opp_table_indexed(struct device *dev, int index, bool getclk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1442
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add
  - drivers/opp/core.c:dev_pm_opp_set_config
```
**Symbols:**

```
ffffffff82129d4c-ffffffff82129d60: _add_opp_table_indexed.cold (STB_LOCAL)
ffffffff81d92930-ffffffff81d92c0d: _add_opp_table_indexed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct opp_table *_add_opp_table_indexed(struct device *dev, int index, bool getclk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1553
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_add_dynamic
  - drivers/opp/core.c:dev_pm_opp_set_config
```
**Symbols:**

```
ffffffff8220ba80-ffffffff8220ba94: _add_opp_table_indexed.cold (STB_LOCAL)
ffffffff81e4a210-ffffffff81e4a502: _add_opp_table_indexed (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool getclk</code>
</li>
</ul>
</details>
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
