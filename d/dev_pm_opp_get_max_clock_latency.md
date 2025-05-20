# Function: <code>dev_pm_opp_get_max_clock_latency</code>

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
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff817d4240)
Location: drivers/opp/core.c:178
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff817d4240-ffffffff817d4274: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8181cfa0)
Location: drivers/opp/core.c:176
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff8181cfa0-ffffffff8181cfce: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81848cb0)
Location: drivers/opp/core.c:160
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81848cb0-ffffffff81848cde: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8188bb70)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff8188bb70-ffffffff8188bba8: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818bdc50)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff818bdc50-ffffffff818bdc88: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff8198f6ba)
Location: drivers/opp/core.c:175
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81991392-ffffffff819913ad: dev_pm_opp_get_max_clock_latency.cold (STB_LOCAL)
ffffffff8198e650-ffffffff8198e6df: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff819936ba)
Location: drivers/opp/core.c:175
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81c290bc-ffffffff81c290d7: dev_pm_opp_get_max_clock_latency.cold (STB_LOCAL)
ffffffff819923a0-ffffffff8199242f: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81977f9a)
Location: drivers/opp/core.c:205
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81c1b1d0-ffffffff81c1b1eb: dev_pm_opp_get_max_clock_latency.cold (STB_LOCAL)
ffffffff81976a00-ffffffff81976a8f: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81a20eea)
Location: drivers/opp/core.c:205
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81d2b24f-ffffffff81d2b26a: dev_pm_opp_get_max_clock_latency.cold (STB_LOCAL)
ffffffff81a1f7d0-ffffffff81a1f85f: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (ffffffff81b89ca9)
Location: drivers/opp/core.c:230
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81ef7424-ffffffff81ef743c: dev_pm_opp_get_max_clock_latency.cold (STB_LOCAL)
ffffffff81b88250-ffffffff81b882ea: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d29429)
Location: drivers/opp/core.c:274
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81d27d00-ffffffff81d27d97: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d925c9)
Location: drivers/opp/core.c:277
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81d90ea0-ffffffff81d90f37: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e49ef9)
Location: drivers/opp/core.c:276
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81e48570-ffffffff81e48607: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
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
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffff800010b18998)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffff800010b18998-ffff800010b189ec: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c0bf38a4)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
c0bf38a4-c0bf38e0: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (c000000000c0a1d0)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
c000000000c0a1d0-c000000000c0a23c: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffe000701540)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffe000701540-ffffffe00070158a: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
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
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81862370)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff81862370-ffffffff818623a8: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff8182b020)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff8182b020-ffffffff8182b058: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818b3100)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff818b3100-ffffffff818b3138: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int dev_pm_opp_get_max_clock_latency(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff818cf3b0)
Location: drivers/opp/core.c:175
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_get_max_transition_latency
```
**Symbols:**

```
ffffffff818cf3b0-ffffffff818cf3e8: dev_pm_opp_get_max_clock_latency (STB_GLOBAL)
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
