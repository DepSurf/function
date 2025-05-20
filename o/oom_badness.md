# Function: <code>oom_badness</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190850)
Location: mm/oom_kill.c:159
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81190850-ffffffff81190974: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a4c10)
Location: mm/oom_kill.c:164
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff811a4c10-ffffffff811a4d82: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b52c0)
Location: mm/oom_kill.c:169
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff811b52c0-ffffffff811b5432: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bcfe0)
Location: mm/oom_kill.c:172
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff811bcfe0-ffffffff811bd150: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1bf0)
Location: mm/oom_kill.c:193
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff811d1bf0-ffffffff811d1d5d: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f2a20)
Location: mm/oom_kill.c:195
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff811f2a20-ffffffff811f2b4a: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81204a40)
Location: mm/oom_kill.c:203
Inline: True
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81204a40-ffffffff81204b6a: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff8121bde0)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff8121bde0-ffffffff8121bf09: oom_badness.part.0 (STB_LOCAL)
ffffffff8121c7e0-ffffffff8121c802: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81229770)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81229770-ffffffff81229899: oom_badness.part.0 (STB_LOCAL)
ffffffff8122a1b0-ffffffff8122a1d2: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81256410)
Location: mm/oom_kill.c:199
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81256410-ffffffff812565be: oom_badness.part.0 (STB_LOCAL)
ffffffff81256f80-ffffffff81256fa2: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81261090)
Location: mm/oom_kill.c:203
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81261090-ffffffff812611cd: oom_badness.part.0 (STB_LOCAL)
ffffffff81261b60-ffffffff81261b8a: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812660f0)
Location: mm/oom_kill.c:203
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff812660f0-ffffffff81266249: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a2910)
Location: mm/oom_kill.c:204
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff812a2910-ffffffff812a2a69: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812fa670)
Location: mm/oom_kill.c:201
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_evaluate_task
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff812fa670-ffffffff812fa851: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81364e20)
Location: mm/oom_kill.c:201
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_evaluate_task
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81364e20-ffffffff81365001: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813972e0)
Location: mm/oom_kill.c:201
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_evaluate_task
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff813972e0-ffffffff813974c4: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c1110)
Location: mm/oom_kill.c:201
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_evaluate_task
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff813c1110-ffffffff813c12f4: oom_badness (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffff8000102b74c0)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffff8000102b74c0-ffff8000102b75dc: oom_badness.part.0 (STB_LOCAL)
ffff8000102b8160-ffff8000102b81bc: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (c04e4198)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
c04e4198-c04e4298: oom_badness.part.0 (STB_LOCAL)
c04e4918-c04e4954: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (c00000000036f110)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
c00000000036f110-c00000000036f2c0: oom_badness.part.0 (STB_LOCAL)
c000000000370200-c000000000370238: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffe0001db7ea)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffe0001db7ea-ffffffe0001db946: oom_badness.part.0 (STB_LOCAL)
ffffffe0001dbf9a-ffffffe0001dbfe4: oom_badness (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81221dc0)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81221dc0-ffffffff81221ee9: oom_badness.part.0 (STB_LOCAL)
ffffffff81222800-ffffffff81222822: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81214f70)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff81214f70-ffffffff81215099: oom_badness.part.0 (STB_LOCAL)
ffffffff812159b0-ffffffff812159d2: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff8121fb60)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff8121fb60-ffffffff8121fc89: oom_badness.part.0 (STB_LOCAL)
ffffffff812205a0-ffffffff812205c2: oom_badness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int oom_badness(struct task_struct *p, long unsigned int totalpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff8122ec20)
Location: mm/oom_kill.c:198
Inline: True
Direct callers:
  - fs/proc/base.c:proc_oom_score
```
**Symbols:**

```
ffffffff8122ec20-ffffffff8122ed66: oom_badness.part.0 (STB_LOCAL)
ffffffff8122f6d0-ffffffff8122f6f2: oom_badness (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param removed. </b>
<code>const nodemask_t *nodemask</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, memcg, nodemask, totalpages</code> ➡️ <code>p, totalpages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
