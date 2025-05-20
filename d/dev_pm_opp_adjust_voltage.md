# Function: <code>dev_pm_opp_adjust_voltage</code>

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
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d5a70)
Location: drivers/opp/core.c:1772
Inline: False
```
**Symbols:**

```
ffffffff817d5a70-ffffffff817d5b96: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181e720)
Location: drivers/opp/core.c:1663
Inline: False
```
**Symbols:**

```
ffffffff8181e720-ffffffff8181e846: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2231
Inline: False
```
**Symbols:**

```
ffffffff81991863-ffffffff8199189d: dev_pm_opp_adjust_voltage.cold (STB_LOCAL)
ffffffff81990e90-ffffffff81991083: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2328
Inline: False
```
**Symbols:**

```
ffffffff81c29359-ffffffff81c29393: dev_pm_opp_adjust_voltage.cold (STB_LOCAL)
ffffffff81993080-ffffffff81993273: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2702
Inline: False
```
**Symbols:**

```
ffffffff81c1b49e-ffffffff81c1b4d8: dev_pm_opp_adjust_voltage.cold (STB_LOCAL)
ffffffff81977970-ffffffff81977b5f: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2712
Inline: False
```
**Symbols:**

```
ffffffff81d2b5fd-ffffffff81d2b637: dev_pm_opp_adjust_voltage.cold (STB_LOCAL)
ffffffff81a20870-ffffffff81a20a5f: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:2852
Inline: False
```
**Symbols:**

```
ffffffff81ef77d1-ffffffff81ef780b: dev_pm_opp_adjust_voltage.cold (STB_LOCAL)
ffffffff81b894a0-ffffffff81b896b1: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28ca0)
Location: drivers/opp/core.c:2854
Inline: False
```
**Symbols:**

```
ffffffff81d28ca0-ffffffff81d28f05: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d91e40)
Location: drivers/opp/core.c:2868
Inline: False
```
**Symbols:**

```
ffffffff81d91e40-ffffffff81d920a5: dev_pm_opp_adjust_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_opp_adjust_voltage(struct device *dev, long unsigned int freq, long unsigned int u_volt, long unsigned int u_volt_min, long unsigned int u_volt_max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e49770)
Location: drivers/opp/core.c:2952
Inline: False
```
**Symbols:**

```
ffffffff81e49770-ffffffff81e499d5: dev_pm_opp_adjust_voltage (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
