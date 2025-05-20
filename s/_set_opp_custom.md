# Function: <code>_set_opp_custom</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849346)
Location: drivers/opp/core.c:600
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
In drivers/opp/core.c (ffffffff8188c1e3)
Location: drivers/opp/core.c:668
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
In drivers/opp/core.c (ffffffff818be353)
Location: drivers/opp/core.c:716
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
In drivers/opp/core.c (ffffffff8198f8cd)
Location: drivers/opp/core.c:756
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff819938c8)
Location: drivers/opp/core.c:754
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
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
In drivers/opp/core.c (ffffffff81978f4f)
Location: drivers/opp/core.c:836
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
In drivers/opp/core.c (ffffffff81a21ecf)
Location: drivers/opp/core.c:836
Inline: True
Inline callers:
  - drivers/opp/core.c:_set_opp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _set_opp_custom(const struct opp_table *opp_table, struct device *dev, struct dev_pm_opp *opp, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81b87010)
Location: drivers/opp/core.c:981
Inline: False
Direct callers:
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff81b87010-ffffffff81b870ee: _set_opp_custom (STB_LOCAL)
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
In drivers/opp/core.c (ffff800010b19234)
Location: drivers/opp/core.c:716
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
In drivers/opp/core.c (c0bf400c)
Location: drivers/opp/core.c:716
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
In drivers/opp/core.c (c000000000c0ad00)
Location: drivers/opp/core.c:716
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
In drivers/opp/core.c (ffffffe000701c90)
Location: drivers/opp/core.c:716
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
In drivers/opp/core.c (ffffffff81862a73)
Location: drivers/opp/core.c:716
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
In drivers/opp/core.c (ffffffff8182b723)
Location: drivers/opp/core.c:716
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
In drivers/opp/core.c (ffffffff818b3803)
Location: drivers/opp/core.c:716
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
In drivers/opp/core.c (ffffffff818cfab3)
Location: drivers/opp/core.c:716
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
</ul>
