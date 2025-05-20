# Function: <code>cpufreq_default_governor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:1005
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81715140-ffffffff81715152: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:967
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81746f20-ffffffff81746f32: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817634a0)
Location: drivers/cpufreq/cpufreq.c:985
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81765590-ffffffff817655a2: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d9460)
Location: drivers/cpufreq/cpufreq.c:1017
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff817db5a0-ffffffff817db5b2: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81822020)
Location: drivers/cpufreq/cpufreq.c:1011
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81824250-ffffffff81824262: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184dea0)
Location: drivers/cpufreq/cpufreq.c:1016
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81850110-ffffffff81850122: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81891020)
Location: drivers/cpufreq/cpufreq.c:1040
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81893640-ffffffff81893652: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c30f0)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818c5660-ffffffff818c5672: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81995500)
Location: drivers/cpufreq/cpufreq.c:1057
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81998920-ffffffff81998932: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81108a40)
Location: kernel/sched/cpufreq_schedutil.c:937
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_init_policy
```
**Symbols:**

```
ffffffff81108a40-ffffffff81108a52: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a920)
Location: kernel/sched/cpufreq_schedutil.c:824
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff8110a920-ffffffff8110a932: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811290b0)
Location: kernel/sched/cpufreq_schedutil.c:831
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff811290b0-ffffffff811290c2: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81145f00)
Location: kernel/sched/cpufreq_schedutil.c:831
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81145f00-ffffffff81145f16: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811730c0)
Location: kernel/sched/cpufreq_schedutil.c:830
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff811730c0-ffffffff811730d6: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81183fb0)
Location: kernel/sched/cpufreq_schedutil.c:834
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81183fb0-ffffffff81183fc6: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811926c0)
Location: kernel/sched/cpufreq_schedutil.c:899
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff811926c0-ffffffff811926d6: cpufreq_default_governor (STB_GLOBAL)
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
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b209d8)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffff800010b23498-ffff800010b234b8: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bfb0a0)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: True
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c0bfd694-c0bfd6b4: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c144b0)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
c000000000c17a60-c000000000c17a7c: cpufreq_default_governor (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81867810)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81869d80-ffffffff81869d92: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818304c0)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff81832a30-ffffffff81832a42: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b85a0)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818bab10-ffffffff818bab22: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cpufreq_governor *cpufreq_default_governor();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d4860)
Location: drivers/cpufreq/cpufreq.c:1046
Inline: False
Direct callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
```
**Symbols:**

```
ffffffff818d6de0-ffffffff818d6df2: cpufreq_default_governor (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
