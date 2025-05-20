# Function: <code>sugov_fast_switch</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e34b0)
Location: kernel/sched/cpufreq_schedutil.c:115
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810e34b0-ffffffff810e3541: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810edb80)
Location: kernel/sched/cpufreq_schedutil.c:111
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810edb80-ffffffff810edc11: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f4970)
Location: kernel/sched/cpufreq_schedutil.c:116
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810f4970-ffffffff810f4a07: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff811005d0)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff811005d0-ffffffff8110067c: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110b110)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff8110b110-ffffffff8110b1bc: sugov_fast_switch (STB_LOCAL)
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
In kernel/sched/cpufreq_schedutil.c (ffffffff8110882f)
Location: kernel/sched/cpufreq_schedutil.c:117
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single_freq
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffff800010164d08)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffff800010164d08-ffff800010164e44: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c03b135c)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
c03b135c-c03b1470: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (c0000000001bbd90)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
c0000000001bbd90-c0000000001bbf1c: sugov_fast_switch (STB_LOCAL)
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
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f98e0)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810f98e0-ffffffff810f998c: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810e9ac0)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810e9ac0-ffffffff810e9b6c: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff810f6b00)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff810f6b00-ffffffff810f6bac: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sugov_fast_switch(struct sugov_policy *sg_policy, u64 time, unsigned int next_freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpufreq_schedutil.c (ffffffff81101b60)
Location: kernel/sched/cpufreq_schedutil.c:114
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_update_shared
  - kernel/sched/cpufreq_schedutil.c:sugov_update_single
```
**Symbols:**

```
ffffffff81101b60-ffffffff81101c21: sugov_fast_switch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
