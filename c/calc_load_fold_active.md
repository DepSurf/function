# Function: <code>calc_load_fold_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b0d40)
Location: kernel/sched/loadavg.c:81
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_load_enter_idle
  - kernel/sched/loadavg.c:calc_global_load_tick
Direct callers:
  - kernel/sched/core.c:migration_call
```
**Symbols:**

```
ffffffff810b0d40-ffffffff810b0d75: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b3bec)
Location: kernel/sched/loadavg.c:81
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_enter_idle
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810b38a0-ffffffff810b38d8: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810ba22c)
Location: kernel/sched/loadavg.c:81
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_enter_idle
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810b9ee0-ffffffff810b9f18: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b4a7c)
Location: kernel/sched/loadavg.c:82
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810b4740-ffffffff810b4773: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810bbd48)
Location: kernel/sched/loadavg.c:83
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810bba10-ffffffff810bba43: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c3418)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810c30e0-ffffffff810c3113: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810cc6c8)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810cc320-ffffffff810cc353: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d4afc)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810d4760-ffffffff810d4797: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810df0bc)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810ded60-ffffffff810ded97: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e739c)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810e6f80-ffffffff810e6fb7: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e4fdc)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810e4bc0-ffffffff810e4bf7: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e6f8c)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810e6b80-ffffffff810e6bb7: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810fe55c)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810fe150-ffffffff810fe18a: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81148b18)
Location: kernel/sched/loadavg.c:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff81148270-ffffffff811482b5: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177348)
Location: kernel/sched/loadavg.c:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff81176a20-ffffffff81176a65: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81187f98)
Location: kernel/sched/loadavg.c:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff81187660-ffffffff811876a5: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81196748)
Location: kernel/sched/loadavg.c:78
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load_tick
  - kernel/sched/build_utility.c:calc_load_nohz_remote
  - kernel/sched/build_utility.c:calc_load_nohz_start
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff81195e20-ffffffff81195e65: calc_load_fold_active (STB_GLOBAL)
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
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffff80001013ec14)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffff80001013e800-ffff80001013e85c: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c038eb4c)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
c038e7c0-c038e800: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c00000000018dda8)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
c00000000018d980-c00000000018d9c8: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffe0000ed47c)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_remote
  - kernel/sched/loadavg.c:calc_load_nohz_start
```
**Symbols:**

```
ffffffe0000ed032-ffffffe0000ed088: calc_load_fold_active (STB_GLOBAL)
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
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d92ac)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810d8f50-ffffffff810d8f87: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c7cac)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810c7950-ffffffff810c7987: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d55ec)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810d5290-ffffffff810d52c7: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int calc_load_fold_active(struct rq *this_rq, long int adjust);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e0e9c)
Location: kernel/sched/loadavg.c:79
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load_tick
  - kernel/sched/loadavg.c:calc_load_nohz_fold
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810e0b40-ffffffff810e0b77: calc_load_fold_active (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int adjust</code>
</li>
</ul>
</details>
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
