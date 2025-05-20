# Function: <code>cpuacct_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810c99b0)
Location: kernel/sched/cpuacct.c:235
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810c99b0-ffffffff810c99e9: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810ce240)
Location: kernel/sched/cpuacct.c:348
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810ce240-ffffffff810ce2b7: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d4260)
Location: kernel/sched/cpuacct.c:348
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810d4260-ffffffff810d42d7: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810d33f0)
Location: kernel/sched/cpuacct.c:348
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810d33f0-ffffffff810d346a: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810dafc0)
Location: kernel/sched/cpuacct.c:349
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810dafc0-ffffffff810db03c: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e3130)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810e3130-ffffffff810e31ab: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810ed860)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810ed860-ffffffff810ed8db: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f4600)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810f4600-ffffffff810f465b: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81100290)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81100290-ffffffff811002eb: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff8110a920)
Location: kernel/sched/cpuacct.c:339
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff8110a920-ffffffff8110a98d: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81107830)
Location: kernel/sched/cpuacct.c:339
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81107830-ffffffff8110789a: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81109900)
Location: kernel/sched/cpuacct.c:339
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81109900-ffffffff8110996a: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff81127dd0)
Location: kernel/sched/cpuacct.c:329
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81127dd0-ffffffff81127e07: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114407a)
Location: kernel/sched/cpuacct.c:334
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
**Symbols:**

```
ffffffff81145480-ffffffff81145511: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116fd49)
Location: kernel/sched/cpuacct.c:334
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
**Symbols:**

```
ffffffff811725d0-ffffffff81172661: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117e6d9)
Location: kernel/sched/cpuacct.c:334
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:put_prev_task_stop
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
```
**Symbols:**

```
ffffffff81183640-ffffffff811836d1: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81191d80)
Location: kernel/sched/cpuacct.c:334
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
**Symbols:**

```
ffffffff81191d80-ffffffff81191e11: cpuacct_charge (STB_GLOBAL)
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
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffff8000101648d8)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffff8000101648d8-ffff800010164954: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (c03b0f10)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
c03b0f10-c03b0fa0: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (c0000000001bb840)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
c0000000001bb840-c0000000001bb8a8: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffe00010814e)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffe00010814e-ffffffe0001081be: cpuacct_charge (STB_GLOBAL)
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
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f95a0)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810f95a0-ffffffff810f95fb: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810e9780)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810e9780-ffffffff810e97db: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff810f67c0)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff810f67c0-ffffffff810f681b: cpuacct_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpuacct_charge(struct task_struct *tsk, u64 cputime);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpuacct.c (ffffffff811017e0)
Location: kernel/sched/cpuacct.c:338
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff811017e0-ffffffff81101858: cpuacct_charge (STB_GLOBAL)
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
