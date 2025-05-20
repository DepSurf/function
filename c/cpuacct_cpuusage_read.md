# Function: <code>cpuacct_cpuusage_read</code>

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
In kernel/sched/cpuacct.c (ffffffff810c97b0)
Location: kernel/sched/cpuacct.c:99
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810cdfe2)
Location: kernel/sched/cpuacct.c:108
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810cdfa0-ffffffff810cdfab: cpuacct_cpuusage_read.isra.4.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d3fef)
Location: kernel/sched/cpuacct.c:108
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810d3fb0-ffffffff810d3fbb: cpuacct_cpuusage_read.isra.4.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d31b0)
Location: kernel/sched/cpuacct.c:108
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810d3150-ffffffff810d315b: cpuacct_cpuusage_read.isra.4.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810dad86)
Location: kernel/sched/cpuacct.c:109
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810dad30-ffffffff810dad3b: cpuacct_cpuusage_read.isra.4.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e2eb0)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810e2eb0-ffffffff810e2eda: cpuacct_cpuusage_read.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810ed5e0)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810ed5e0-ffffffff810ed60a: cpuacct_cpuusage_read.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f4370)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810f4370-ffffffff810f439e: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81100000)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff81100000-ffffffff8110002e: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff8110a7ac)
Location: kernel/sched/cpuacct.c:99
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff811076bc)
Location: kernel/sched/cpuacct.c:99
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff8110977c)
Location: kernel/sched/cpuacct.c:99
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct *ca, int cpu, enum cpuacct_stat_index index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81127ccd)
Location: kernel/sched/cpuacct.c:95
Inline: True
Inline callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:cpuusage_read
  - kernel/sched/cpuacct.c:cpuusage_sys_read
  - kernel/sched/cpuacct.c:cpuusage_user_read
Direct callers:
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
  - kernel/sched/cpuacct.c:cpuacct_all_seq_show
```
**Symbols:**

```
ffffffff811277a0-ffffffff81127859: cpuacct_cpuusage_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct *ca, int cpu, enum cpuacct_stat_index index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141fed)
Location: kernel/sched/cpuacct.c:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:cpuusage_read
  - kernel/sched/build_utility.c:cpuusage_sys_read
  - kernel/sched/build_utility.c:cpuusage_user_read
Direct callers:
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
```
**Symbols:**

```
ffffffff8113c160-ffffffff8113c23b: cpuacct_cpuusage_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct *ca, int cpu, enum cpuacct_stat_index index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116df22)
Location: kernel/sched/cpuacct.c:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:__cpuusage_read
Direct callers:
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
```
**Symbols:**

```
ffffffff81166da0-ffffffff81166e7b: cpuacct_cpuusage_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct *ca, int cpu, enum cpuacct_stat_index index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117d6ed)
Location: kernel/sched/cpuacct.c:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__cpuusage_read
Direct callers:
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
```
**Symbols:**

```
ffffffff81177170-ffffffff8117724b: cpuacct_cpuusage_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct *ca, int cpu, enum cpuacct_stat_index index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118b3bd)
Location: kernel/sched/cpuacct.c:94
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__cpuusage_read
Direct callers:
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
```
**Symbols:**

```
ffffffff811850e0-ffffffff811851bb: cpuacct_cpuusage_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffff800010164550)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffff800010164550-ffff8000101645c0: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 cpuacct_cpuusage_read(struct cpuacct *ca, int cpu, enum cpuacct_stat_index index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (c03b0ad8)
Location: kernel/sched/cpuacct.c:98
Inline: False
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
c03b0ad8-c03b0b74: cpuacct_cpuusage_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (c0000000001bb460)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
c0000000001bb460-c0000000001bb4c0: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffe000107e26)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffe000107e26-ffffffe000107e8a: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f9310)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810f9310-ffffffff810f933e: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e94f0)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810e94f0-ffffffff810e951e: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f6530)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff810f6530-ffffffff810f655e: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81101550)
Location: kernel/sched/cpuacct.c:98
Inline: True
Direct callers:
  - kernel/sched/cpuacct.c:__cpuacct_percpu_seq_show
  - kernel/sched/cpuacct.c:__cpuusage_read
```
**Symbols:**

```
ffffffff81101550-ffffffff8110157e: cpuacct_cpuusage_read.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
