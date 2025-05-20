# Function: <code>cpufreq_enable_fast_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81711640)
Location: drivers/cpufreq/cpufreq.c:459
Inline: True
```
**Symbols:**

```
ffffffff81711640-ffffffff817116e9: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817433e0)
Location: drivers/cpufreq/cpufreq.c:459
Inline: True
```
**Symbols:**

```
ffffffff817433e0-ffffffff81743489: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81761aa0)
Location: drivers/cpufreq/cpufreq.c:459
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81761aa0-ffffffff81761b4a: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff817d7a80)
Location: drivers/cpufreq/cpufreq.c:465
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff817d7a80-ffffffff817d7b2a: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (0)
Location: drivers/cpufreq/cpufreq.c:450
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818230ff-ffffffff8182315b: cpufreq_enable_fast_switch.cold.39 (STB_LOCAL)
ffffffff818203e0-ffffffff81820434: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8184c2a9)
Location: drivers/cpufreq/cpufreq.c:450
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff8184efbf-ffffffff8184f01b: cpufreq_enable_fast_switch.cold.41 (STB_LOCAL)
ffffffff8184c290-ffffffff8184c2e4: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8188f237)
Location: drivers/cpufreq/cpufreq.c:480
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818923d2-ffffffff8189242b: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff8188f220-ffffffff8188f270: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818c1447)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818c44a6-ffffffff818c44ff: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff818c1430-ffffffff818c1480: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff819930a7)
Location: drivers/cpufreq/cpufreq.c:488
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81996661-ffffffff819966ba: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81993090-ffffffff819930e3: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81996257)
Location: drivers/cpufreq/cpufreq.c:494
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81c296cb-ffffffff81c29724: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81996240-ffffffff81996293: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8197b027)
Location: drivers/cpufreq/cpufreq.c:491
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81c1ba72-ffffffff81c1bacb: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff8197b010-ffffffff8197b063: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81a245cc)
Location: drivers/cpufreq/cpufreq.c:491
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81d2bde4-ffffffff81d2be52: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81a245a0-ffffffff81a24607: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81b8dcf6)
Location: drivers/cpufreq/cpufreq.c:492
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff81ef8034-ffffffff81ef80a2: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81b8dcc0-ffffffff81b8dd3b: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d2d6a6)
Location: drivers/cpufreq/cpufreq.c:492
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff820a8ca1-ffffffff820a8cb6: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81d2d670-ffffffff81d2d740: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81d96926)
Location: drivers/cpufreq/cpufreq.c:499
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff82129eba-ffffffff82129ecf: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81d968f0-ffffffff81d969c0: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81e4e586)
Location: drivers/cpufreq/cpufreq.c:500
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff8220bc94-ffffffff8220bca9: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81e4e550-ffffffff81e4e620: cpufreq_enable_fast_switch (STB_GLOBAL)
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
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffff800010b1dd58)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffff800010b1dd58-ffff800010b1de28: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c0bf9264)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c0bf9264-c0bf9328: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq.c (c000000000c118c0)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c000000000c118c0-c000000000c119d4: cpufreq_enable_fast_switch (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff81865b67)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81868bc6-ffffffff81868c1f: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff81865b50-ffffffff81865ba0: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff8182e817)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff81831876-ffffffff818318cf: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff8182e800-ffffffff8182e850: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818b68f7)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818b9956-ffffffff818b99af: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff818b68e0-ffffffff818b6930: cpufreq_enable_fast_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void cpufreq_enable_fast_switch(struct cpufreq_policy *policy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/cpufreq/cpufreq.c (ffffffff818d2dd7)
Location: drivers/cpufreq/cpufreq.c:483
Inline: True
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff818d5c36-ffffffff818d5c8f: cpufreq_enable_fast_switch.cold (STB_LOCAL)
ffffffff818d2dc0-ffffffff818d2e10: cpufreq_enable_fast_switch (STB_GLOBAL)
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
