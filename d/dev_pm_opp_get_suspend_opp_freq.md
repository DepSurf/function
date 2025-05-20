# Function: <code>dev_pm_opp_get_suspend_opp_freq</code>

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
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4440)
Location: drivers/opp/core.c:287
Inline: False
```
**Symbols:**

```
ffffffff817d4440-ffffffff817d4496: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181d160)
Location: drivers/opp/core.c:285
Inline: False
```
**Symbols:**

```
ffffffff8181d160-ffffffff8181d1ab: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848e80)
Location: drivers/opp/core.c:269
Inline: False
```
**Symbols:**

```
ffffffff81848e80-ffffffff81848ecb: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188bd60)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8188bd60-ffffffff8188bdb9: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bde40)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818bde40-ffffffff818bde99: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8199142f-ffffffff81991462: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff8198e8d0-ffffffff8198e984: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81c29171-ffffffff81c291a4: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff819926b0-ffffffff81992764: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:314
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81c1b285-ffffffff81c1b2b8: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff81976d10-ffffffff81976dc4: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:314
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81d2b304-ffffffff81d2b362: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff81a1fae0-ffffffff81a1fba9: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:339
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81ef74e1-ffffffff81ef7539: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff81b88660-ffffffff81b88731: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:383
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff820a8ab4-ffffffff820a8ae1: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff81d285a0-ffffffff81d286a0: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:386
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff82129c8a-ffffffff82129cb7: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff81d91740-ffffffff81d91840: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:385
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8220b9d3-ffffffff8220ba00: dev_pm_opp_get_suspend_opp_freq.cold (STB_LOCAL)
ffffffff81e49070-ffffffff81e4916a: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
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
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18be8)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffff800010b18be8-ffff800010b18c60: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf3a9c)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
c0bf3a9c-c0bf3b04: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a4c0)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
c000000000c0a4c0-c000000000c0a56c: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701706)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffe000701706-ffffffe000701770: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
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
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81862560)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81862560-ffffffff818625b9: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182b210)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff8182b210-ffffffff8182b269: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b32f0)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818b32f0-ffffffff818b3349: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_suspend_opp_freq(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cf5a0)
Location: drivers/opp/core.c:284
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818cf5a0-ffffffff818cf5f9: dev_pm_opp_get_suspend_opp_freq (STB_GLOBAL)
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
