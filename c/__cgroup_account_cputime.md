# Function: <code>__cgroup_account_cputime</code>

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
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/stat.c (ffffffff81135620)
Location: kernel/cgroup/stat.c:226
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81135620-ffffffff8113564a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81144050)
Location: kernel/cgroup/rstat.c:362
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81144050-ffffffff8114407a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8114fb60)
Location: kernel/cgroup/rstat.c:362
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff8114fb60-ffffffff8114fb8a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115ba60)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff8115ba60-ffffffff8115ba8a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81167680)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81167680-ffffffff811676aa: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81178ee0)
Location: kernel/cgroup/rstat.c:359
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81178ee0-ffffffff81178f0a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81175bf0)
Location: kernel/cgroup/rstat.c:358
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81175bf0-ffffffff81175c1a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81176770)
Location: kernel/cgroup/rstat.c:368
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81176770-ffffffff8117679a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8119dff0)
Location: kernel/cgroup/rstat.c:368
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff8119dff0-ffffffff8119e01a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff811ce300)
Location: kernel/cgroup/rstat.c:373
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff811ce300-ffffffff811ce355: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81211ac0)
Location: kernel/cgroup/rstat.c:409
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81211ac0-ffffffff81211b15: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81227420)
Location: kernel/cgroup/rstat.c:393
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/build_policy.c:update_curr_dl
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81227420-ffffffff81227475: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8123f230)
Location: kernel/cgroup/rstat.c:440
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/fair.c:update_curr_common
```
**Symbols:**

```
ffffffff8123f230-ffffffff8123f285: __cgroup_account_cputime (STB_GLOBAL)
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
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffff8000101d9cd8)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffff8000101d9cd8-ffff8000101d9d20: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c041c60c)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
c041c60c-c041c67c: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (c000000000246ef0)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
c000000000246ef0-c000000000246f3c: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffe0001525d2)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffe0001525d2-ffffffe000152628: __cgroup_account_cputime (STB_GLOBAL)
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
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115fca0)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff8115fca0-ffffffff8115fcca: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff81152f20)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff81152f20-ffffffff81152f4a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8115da70)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff8115da70-ffffffff8115da9a: __cgroup_account_cputime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __cgroup_account_cputime(struct cgroup *cgrp, u64 delta_exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/rstat.c (ffffffff8116acc0)
Location: kernel/cgroup/rstat.c:365
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_curr
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:update_curr_dl
  - kernel/sched/stop_task.c:put_prev_task_stop
```
**Symbols:**

```
ffffffff8116acc0-ffffffff8116acea: __cgroup_account_cputime (STB_GLOBAL)
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
