# Function: <code>_set_opp</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _set_opp(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:985
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81978e90-ffffffff8197949e: _set_opp (STB_LOCAL)
ffffffff81c1b69b-ffffffff81c1b7d4: _set_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _set_opp(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:995
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81a21e10-ffffffff81a22456: _set_opp (STB_LOCAL)
ffffffff81d2b881-ffffffff81d2ba2a: _set_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _set_opp(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1140
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81b8aed0-ffffffff81b8b4e0: _set_opp (STB_LOCAL)
ffffffff81ef7a67-ffffffff81ef7c44: _set_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _set_opp(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, void *clk_data, bool forced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1067
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81d2a4e0-ffffffff81d2a9f7: _set_opp (STB_LOCAL)
ffffffff820a8b75-ffffffff820a8bc0: _set_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _set_opp(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, void *clk_data, bool forced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1080
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81d936d0-ffffffff81d93c75: _set_opp (STB_LOCAL)
ffffffff82129d60-ffffffff82129daf: _set_opp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _set_opp(struct device *dev, struct opp_table *opp_table, struct dev_pm_opp *opp, void *clk_data, bool forced);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1185
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_opp
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81e4b120-ffffffff81e4b6ca: _set_opp (STB_LOCAL)
ffffffff8220baf7-ffffffff8220bb46: _set_opp.cold (STB_LOCAL)
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
<b>Param added. </b>
<code>void *clk_data</code>
</li>
<li>
<b>Param added. </b>
<code>bool forced</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int freq</code>
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
