# Function: <code>_dev_pm_opp_find_and_remove_table</code>

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
void _dev_pm_opp_find_and_remove_table(struct device *dev, bool remove_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d5c70)
Location: drivers/opp/core.c:1940
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff817d5c70-ffffffff817d5ced: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev, bool remove_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181e920)
Location: drivers/opp/core.c:1831
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
```
**Symbols:**

```
ffffffff8181e920-ffffffff8181e9a4: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8184a790)
Location: drivers/opp/core.c:2027
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8184a790-ffffffff8184a80c: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188d400)
Location: drivers/opp/core.c:2144
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8188d400-ffffffff8188d479: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bf660)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff818bf660-ffffffff818bf6d9: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2376
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8199189d-ffffffff819918e5: _dev_pm_opp_find_and_remove_table.cold (STB_LOCAL)
ffffffff81991090-ffffffff8199115a: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
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
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b1aa90)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_remove_table
```
**Symbols:**

```
ffff800010b1aa90-ffff800010b1ab24: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf55a8)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_remove_table
```
**Symbols:**

```
c0bf55a8-c0bf5650: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0c970)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_remove_table
```
**Symbols:**

```
c000000000c0c970-c000000000c0ca5c: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe0007030b6)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/opp/of.c:dev_pm_opp_of_remove_table
```
**Symbols:**

```
ffffffe0007030b6-ffffffe000703144: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
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
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81863d80)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff81863d80-ffffffff81863df9: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182ca30)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff8182ca30-ffffffff8182caa9: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b4b10)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff818b4b10-ffffffff818b4b89: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _dev_pm_opp_find_and_remove_table(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818d0dc0)
Location: drivers/opp/core.c:2193
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_remove_table
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
```
**Symbols:**

```
ffffffff818d0dc0-ffffffff818d0e39: _dev_pm_opp_find_and_remove_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool remove_all</code>
</li>
</ul>
</details>
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
