# Function: <code>devfreq_recommended_opp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ebd50)
Location: drivers/devfreq/devfreq.c:1098
Inline: False
```
**Symbols:**

```
ffffffff816ebd50-ffffffff816ebd62: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff817509c0)
Location: drivers/devfreq/devfreq.c:1222
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff817509c0-ffffffff817509d2: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177c740)
Location: drivers/devfreq/devfreq.c:1257
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8177c740-ffffffff8177c752: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179b2d0)
Location: drivers/devfreq/devfreq.c:1248
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8179b2d0-ffffffff8179b2e2: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818137d0)
Location: drivers/devfreq/devfreq.c:1310
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818137d0-ffffffff8181381c: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185d690)
Location: drivers/devfreq/devfreq.c:1313
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8185d690-ffffffff8185d6dc: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187ccf0)
Location: drivers/devfreq/devfreq.c:1460
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8187ccf0-ffffffff8187cd3c: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818c71a0)
Location: drivers/devfreq/devfreq.c:1485
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818c71a0-ffffffff818c71ee: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818f9100)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818f9100-ffffffff818f914e: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cef90)
Location: drivers/devfreq/devfreq.c:1755
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff819cef90-ffffffff819cefde: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819ceb70)
Location: drivers/devfreq/devfreq.c:1981
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff819ceb70-ffffffff819cebbe: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b3cd0)
Location: drivers/devfreq/devfreq.c:1999
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff819b3cd0-ffffffff819b3d1e: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81a628b0)
Location: drivers/devfreq/devfreq.c:1999
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81a628b0-ffffffff81a628fe: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81bd3cd0)
Location: drivers/devfreq/devfreq.c:2027
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81bd3cd0-ffffffff81bd3d26: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7fc50)
Location: drivers/devfreq/devfreq.c:2029
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81d7fc50-ffffffff81d7fca6: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81dedfe0)
Location: drivers/devfreq/devfreq.c:2030
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81dedfe0-ffffffff81dee036: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea4490)
Location: drivers/devfreq/devfreq.c:2069
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp
```
**Symbols:**

```
ffffffff81ea4490-ffffffff81ea44ef: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b85d30)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffff800010b85d30-ffff800010b85da8: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c688e0)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_target
```
**Symbols:**

```
c0c688e0-c0c6893c: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c63bb0)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
c000000000c63bb0-c000000000c63c54: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072ee62)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffe00072ee62-ffffffe00072eed2: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8189a430)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8189a430-ffffffff8189a47e: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81857900)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff81857900-ffffffff8185794e: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818e9b20)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff818e9b20-ffffffff818e9b6e: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dev_pm_opp *devfreq_recommended_opp(struct device *dev, long unsigned int *freq, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8190aba0)
Location: drivers/devfreq/devfreq.c:1498
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq
```
**Symbols:**

```
ffffffff8190aba0-ffffffff8190abee: devfreq_recommended_opp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct dev_pm_opp *</code> ➡️ <code>struct dev_pm_opp *</code>
</li>
</ul>
</details>
</li>
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
