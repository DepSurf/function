# Function: <code>__target_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff816af49c)
Location: drivers/cpufreq/cpufreq.c:1789
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81711837)
Location: drivers/cpufreq/cpufreq.c:1884
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8174406e)
Location: drivers/cpufreq/cpufreq.c:1856
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817625c3)
Location: drivers/cpufreq/cpufreq.c:1859
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d85b6)
Location: drivers/cpufreq/cpufreq.c:1892
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (ffffffff818212ea)
Location: drivers/cpufreq/cpufreq.c:1891
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (ffffffff8184d05a)
Location: drivers/cpufreq/cpufreq.c:1892
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (ffffffff81890356)
Location: drivers/cpufreq/cpufreq.c:2042
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (ffffffff818c2556)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2093
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff81994ba0-ffffffff81994d39: __target_index (STB_LOCAL)
ffffffff81996806-ffffffff81996820: __target_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2166
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff81997a70-ffffffff81997c15: __target_index (STB_LOCAL)
ffffffff81c29852-ffffffff81c2986c: __target_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2172
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff8197c670-ffffffff8197c894: __target_index (STB_LOCAL)
ffffffff81c1bba9-ffffffff81c1bbed: __target_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2178
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff81a259a0-ffffffff81a25bc1: __target_index (STB_LOCAL)
ffffffff81d2bf93-ffffffff81d2bfd7: __target_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:2210
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff81b8eb30-ffffffff81b8ed68: __target_index (STB_LOCAL)
ffffffff81ef81bf-ffffffff81ef81f4: __target_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2ef50)
Location: drivers/cpufreq/cpufreq.c:2207
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff81d2ef50-ffffffff81d2f1bd: __target_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d97fe0)
Location: drivers/cpufreq/cpufreq.c:2214
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff81d97fe0-ffffffff81d98248: __target_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __target_index(struct cpufreq_policy *policy, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4fc60)
Location: drivers/cpufreq/cpufreq.c:2255
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
**Symbols:**

```
ffffffff81e4fc60-ffffffff81e4fec8: __target_index (STB_LOCAL)
```
</details>
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
In drivers/cpufreq/cpufreq.c (ffff800010b1ef38)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (c0bf9508)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (c000000000c11c70)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/cpufreq/cpufreq.c (ffffffff81866c76)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (ffffffff8182f926)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (ffffffff818b7a06)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
In drivers/cpufreq/cpufreq.c (ffffffff818d3006)
Location: drivers/cpufreq/cpufreq.c:2056
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_driver_target
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
