# Function: <code>dev_pm_opp_set_opp</code>

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
int dev_pm_opp_set_opp(struct device *dev, struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1146
Inline: False
```
**Symbols:**

```
ffffffff81c1b84d-ffffffff81c1b885: dev_pm_opp_set_opp.cold (STB_LOCAL)
ffffffff819796a0-ffffffff81979741: dev_pm_opp_set_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_opp(struct device *dev, struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1156
Inline: False
```
**Symbols:**

```
ffffffff81d2bacd-ffffffff81d2bb05: dev_pm_opp_set_opp.cold (STB_LOCAL)
ffffffff81a22680-ffffffff81a22721: dev_pm_opp_set_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_opp(struct device *dev, struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1301
Inline: False
```
**Symbols:**

```
ffffffff81ef7ce6-ffffffff81ef7d1e: dev_pm_opp_set_opp.cold (STB_LOCAL)
ffffffff81b8b710-ffffffff81b8b7bc: dev_pm_opp_set_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_opp_set_opp(struct device *dev, struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d2acd0)
Location: drivers/opp/core.c:1253
Inline: False
```
**Symbols:**

```
ffffffff81d2acd0-ffffffff81d2adc5: dev_pm_opp_set_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_opp_set_opp(struct device *dev, struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d93f50)
Location: drivers/opp/core.c:1266
Inline: False
```
**Symbols:**

```
ffffffff81d93f50-ffffffff81d94045: dev_pm_opp_set_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_opp_set_opp(struct device *dev, struct dev_pm_opp *opp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e4b9b0)
Location: drivers/opp/core.c:1379
Inline: False
```
**Symbols:**

```
ffffffff81e4b9b0-ffffffff81e4baa5: dev_pm_opp_set_opp (STB_GLOBAL)
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
