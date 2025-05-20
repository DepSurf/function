# Function: <code>dev_pm_opp_find_level_ceil</code>

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
struct dev_pm_opp *dev_pm_opp_find_level_ceil(struct device *dev, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:497
Inline: False
```
**Symbols:**

```
ffffffff81c1b368-ffffffff81c1b3a2: dev_pm_opp_find_level_ceil.cold (STB_LOCAL)
ffffffff819771b0-ffffffff819772bd: dev_pm_opp_find_level_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_level_ceil(struct device *dev, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:497
Inline: False
```
**Symbols:**

```
ffffffff81d2b4ae-ffffffff81d2b505: dev_pm_opp_find_level_ceil.cold (STB_LOCAL)
ffffffff81a20120-ffffffff81a2025e: dev_pm_opp_find_level_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_level_ceil(struct device *dev, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:698
Inline: False
```
**Symbols:**

```
ffffffff81ef765e-ffffffff81ef76b6: dev_pm_opp_find_level_ceil.cold (STB_LOCAL)
ffffffff81b88ce0-ffffffff81b88e20: dev_pm_opp_find_level_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_level_ceil(struct device *dev, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28290)
Location: drivers/opp/core.c:718
Inline: False
```
**Symbols:**

```
ffffffff81d28290-ffffffff81d28308: dev_pm_opp_find_level_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_level_ceil(struct device *dev, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91430)
Location: drivers/opp/core.c:721
Inline: False
```
**Symbols:**

```
ffffffff81d91430-ffffffff81d914a8: dev_pm_opp_find_level_ceil (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dev_pm_opp *dev_pm_opp_find_level_ceil(struct device *dev, unsigned int *level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e48bd0)
Location: drivers/opp/core.c:804
Inline: False
```
**Symbols:**

```
ffffffff81e48bd0-ffffffff81e48cfd: dev_pm_opp_find_level_ceil (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
