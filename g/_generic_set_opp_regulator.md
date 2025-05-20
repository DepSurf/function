# Function: <code>_generic_set_opp_regulator</code>

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
In drivers/opp/core.c (ffffffff817d4996)
Location: drivers/opp/core.c:598
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d7c3)
Location: drivers/opp/core.c:605
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849581)
Location: drivers/opp/core.c:551
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188c373)
Location: drivers/opp/core.c:619
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818be4e3)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _generic_set_opp_regulator(struct opp_table *opp_table, struct device *dev, long unsigned int old_freq, long unsigned int freq, struct dev_pm_opp_supply *old_supply, struct dev_pm_opp_supply *new_supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:667
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8198e280-ffffffff8198e3b4: _generic_set_opp_regulator (STB_LOCAL)
ffffffff81991304-ffffffff81991392: _generic_set_opp_regulator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _generic_set_opp_regulator(struct opp_table *opp_table, struct device *dev, long unsigned int old_freq, long unsigned int freq, struct dev_pm_opp_supply *old_supply, struct dev_pm_opp_supply *new_supply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:667
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81991c60-ffffffff81991d8d: _generic_set_opp_regulator (STB_LOCAL)
ffffffff81c2900c-ffffffff81c2909d: _generic_set_opp_regulator.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8197916f)
Location: drivers/opp/core.c:750
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81a220ef)
Location: drivers/opp/core.c:750
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b8b123)
Location: drivers/opp/core.c:895
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1936c)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf4154)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0ae68)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701d90)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81862c03)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182b8b3)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3993)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cfc43)
Location: drivers/opp/core.c:667
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
