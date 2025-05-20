# Function: <code>dev_pm_opp_set_rate</code>

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
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4770)
Location: drivers/opp/core.c:655
Inline: False
```
**Symbols:**

```
ffffffff817d4770-ffffffff817d4d0d: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d440)
Location: drivers/opp/core.c:662
Inline: False
```
**Symbols:**

```
ffffffff8181d440-ffffffff8181da5e: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81849230)
Location: drivers/opp/core.c:686
Inline: False
```
**Symbols:**

```
ffffffff81849230-ffffffff81849746: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff8188d65f-ffffffff8188d7b0: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff8188c0d0-ffffffff8188c4d0: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:805
Inline: False
```
**Symbols:**

```
ffffffff818bf86d-ffffffff818bf9b2: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff818be240-ffffffff818be640: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:845
Inline: False
```
**Symbols:**

```
ffffffff8199161d-ffffffff81991734: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff8198f740-ffffffff8198fd58: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:914
Inline: False
```
**Symbols:**

```
ffffffff81c29401-ffffffff81c294f2: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff81993740-ffffffff81993cfe: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1081
Inline: False
```
**Symbols:**

```
ffffffff81c1b7d4-ffffffff81c1b84d: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff819794a0-ffffffff8197969e: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1091
Inline: False
```
**Symbols:**

```
ffffffff81d2ba2a-ffffffff81d2bacd: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff81a22460-ffffffff81a2267e: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1236
Inline: False
```
**Symbols:**

```
ffffffff81ef7c44-ffffffff81ef7ce6: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff81b8b4e0-ffffffff81b8b70b: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1176
Inline: False
```
**Symbols:**

```
ffffffff820a8bc0-ffffffff820a8be4: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff81d2aa10-ffffffff81d2acb8: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1189
Inline: False
```
**Symbols:**

```
ffffffff82129daf-ffffffff82129dd3: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff81d93c90-ffffffff81d93f38: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:1302
Inline: False
```
**Symbols:**

```
ffffffff8220bb46-ffffffff8220bb6a: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff81e4b6e0-ffffffff81e4b996: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b19140)
Location: drivers/opp/core.c:805
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:set_target
```
**Symbols:**

```
ffff800010b19140-ffff800010b19654: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3f0c)
Location: drivers/opp/core.c:805
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:set_target
  - drivers/devfreq/exynos-bus.c:exynos_bus_target
```
**Symbols:**

```
c0bf3f0c-c0bf43f4: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0ac00)
Location: drivers/opp/core.c:805
Inline: False
```
**Symbols:**

```
c000000000c0ac00-c000000000c0b000: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701bbc)
Location: drivers/opp/core.c:805
Inline: False
```
**Symbols:**

```
ffffffe000701bbc-ffffffe000701ff0: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:805
Inline: False
```
**Symbols:**

```
ffffffff81863f8d-ffffffff818640d2: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff81862960-ffffffff81862d60: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:805
Inline: False
```
**Symbols:**

```
ffffffff8182cc3d-ffffffff8182cd82: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff8182b610-ffffffff8182ba10: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:805
Inline: False
```
**Symbols:**

```
ffffffff818b4d1d-ffffffff818b4e62: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff818b36f0-ffffffff818b3af0: dev_pm_opp_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dev_pm_opp_set_rate(struct device *dev, long unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:805
Inline: False
```
**Symbols:**

```
ffffffff818d0fcd-ffffffff818d1112: dev_pm_opp_set_rate.cold (STB_LOCAL)
ffffffff818cf9a0-ffffffff818cfda0: dev_pm_opp_set_rate (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
