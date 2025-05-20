# Function: <code>cpufreq_driver_fast_switch</code>

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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81710140)
Location: drivers/cpufreq/cpufreq.c:1849
Inline: False
```
**Symbols:**

```
ffffffff81710140-ffffffff81710167: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81742120)
Location: drivers/cpufreq/cpufreq.c:1821
Inline: False
```
**Symbols:**

```
ffffffff81742120-ffffffff81742144: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81760790)
Location: drivers/cpufreq/cpufreq.c:1824
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
**Symbols:**

```
ffffffff81760790-ffffffff817607b4: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d6760)
Location: drivers/cpufreq/cpufreq.c:1857
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_commit
```
**Symbols:**

```
ffffffff817d6760-ffffffff817d678a: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8181f450)
Location: drivers/cpufreq/cpufreq.c:1856
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff8181f450-ffffffff8181f47a: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184b2f0)
Location: drivers/cpufreq/cpufreq.c:1857
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff8184b2f0-ffffffff8184b31a: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188e370)
Location: drivers/cpufreq/cpufreq.c:2007
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff8188e370-ffffffff8188e39a: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c0500)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff818c0500-ffffffff818c052a: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81992490)
Location: drivers/cpufreq/cpufreq.c:2058
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff81992490-ffffffff819924ba: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81997430)
Location: drivers/cpufreq/cpufreq.c:2074
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81997430-ffffffff819974e0: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197c1b0)
Location: drivers/cpufreq/cpufreq.c:2080
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff8197c1b0-ffffffff8197c261: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a25430)
Location: drivers/cpufreq/cpufreq.c:2086
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81a25430-ffffffff81a254db: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8ee00)
Location: drivers/cpufreq/cpufreq.c:2118
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81b8ee00-ffffffff81b8eee0: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2e670)
Location: drivers/cpufreq/cpufreq.c:2115
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81d2e670-ffffffff81d2e760: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d97620)
Location: drivers/cpufreq/cpufreq.c:2122
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81d97620-ffffffff81d97710: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4f2a0)
Location: drivers/cpufreq/cpufreq.c:2163
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:sugov_update_single_freq
```
**Symbols:**

```
ffffffff81e4f2a0-ffffffff81e4f390: cpufreq_driver_fast_switch (STB_GLOBAL)
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1cf08)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffff800010b1cf08-ffff800010b1cf58: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf7dd0)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
c0bf7dd0-c0bf7e14: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c0f970)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
c000000000c0f970-c000000000c0f9e0: cpufreq_driver_fast_switch (STB_GLOBAL)
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
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81864c20)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff81864c20-ffffffff81864c4a: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182d8d0)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff8182d8d0-ffffffff8182d8fa: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b59b0)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff818b59b0-ffffffff818b59da: cpufreq_driver_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int cpufreq_driver_fast_switch(struct cpufreq_policy *policy, unsigned int target_freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d1c60)
Location: drivers/cpufreq/cpufreq.c:2021
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_fast_switch
```
**Symbols:**

```
ffffffff818d1c60-ffffffff818d1c8a: cpufreq_driver_fast_switch (STB_GLOBAL)
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
