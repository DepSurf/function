# Function: <code>cpupri_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810c41b0)
Location: kernel/sched/cpupri.c:140
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:rq_offline_rt
```
**Symbols:**

```
ffffffff810c41b0-ffffffff810c423e: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810c7ea0)
Location: kernel/sched/cpupri.c:140
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810c7ea0-ffffffff810c7f2d: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810cde90)
Location: kernel/sched/cpupri.c:140
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810cde90-ffffffff810cdf17: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810ca7d0)
Location: kernel/sched/cpupri.c:140
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810ca7d0-ffffffff810ca87f: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810d1fe0)
Location: kernel/sched/cpupri.c:140
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810d1fe0-ffffffff810d208f: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810da090)
Location: kernel/sched/cpupri.c:135
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810da090-ffffffff810da143: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810e3be0)
Location: kernel/sched/cpupri.c:135
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810e3be0-ffffffff810e3c93: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810ea7f0)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810ea7f0-ffffffff810ea88b: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810f61c0)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
ffffffff810f61c0-ffffffff810f625b: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810ffb10)
Location: kernel/sched/cpupri.c:186
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
ffffffff810ffb10-ffffffff810ffbab: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810fe5f0)
Location: kernel/sched/cpupri.c:210
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:__dequeue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
**Symbols:**

```
ffffffff810fe5f0-ffffffff810fe67b: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff811009d0)
Location: kernel/sched/cpupri.c:210
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
**Symbols:**

```
ffffffff811009d0-ffffffff81100a60: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff8111ca50)
Location: kernel/sched/cpupri.c:210
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
**Symbols:**

```
ffffffff8111ca50-ffffffff8111cb63: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81148e70)
Location: kernel/sched/cpupri.c:209
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:rq_online_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff81148e70-ffffffff81148fcc: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177710)
Location: kernel/sched/cpupri.c:209
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:rq_online_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff81177710-ffffffff8117786c: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81188340)
Location: kernel/sched/cpupri.c:209
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:rq_online_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff81188340-ffffffff8118849b: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81196c20)
Location: kernel/sched/cpupri.c:210
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
  - kernel/sched/build_policy.c:rq_offline_rt
  - kernel/sched/build_policy.c:rq_online_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff81196c20-ffffffff81196d7b: cpupri_set (STB_GLOBAL)
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
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffff800010159e98)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
ffff800010159e98-ffff80001015a018: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (c03a6cc4)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
c03a6cc4-c03a6dd4: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (c0000000001ae160)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
c0000000001ae160-c0000000001ae29c: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffe0000ff96a)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
ffffffe0000ff96a-ffffffe0000ffa72: cpupri_set (STB_GLOBAL)
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
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810ef5c0)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810ef5c0-ffffffff810ef65b: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810df630)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
ffffffff810df630-ffffffff810df6cb: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810ec6f0)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
**Symbols:**

```
ffffffff810ec6f0-ffffffff810ec78b: cpupri_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpupri_set(struct cpupri *cp, int cpu, int newpri);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810f7730)
Location: kernel/sched/cpupri.c:131
Inline: False
Direct callers:
  - kernel/sched/rt.c:rq_offline_rt
  - kernel/sched/rt.c:rq_online_rt
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:dequeue_rt_stack
```
**Symbols:**

```
ffffffff810f7730-ffffffff810f77cb: cpupri_set (STB_GLOBAL)
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
