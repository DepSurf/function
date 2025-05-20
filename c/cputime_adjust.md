# Function: <code>cputime_adjust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b1540)
Location: kernel/sched/cputime.c:578
Inline: False
Direct callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
```
**Symbols:**

```
ffffffff810b1540-ffffffff810b1670: cputime_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b3fd0)
Location: kernel/sched/cputime.c:597
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
```
**Symbols:**

```
ffffffff810b3fd0-ffffffff810b40f8: cputime_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ba610)
Location: kernel/sched/cputime.c:608
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
```
**Symbols:**

```
ffffffff810ba610-ffffffff810ba738: cputime_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b4e90)
Location: kernel/sched/cputime.c:588
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
```
**Symbols:**

```
ffffffff810b4e90-ffffffff810b4fb6: cputime_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc720)
Location: kernel/sched/cputime.c:594
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/stat.c:cgroup_stat_show_cputime
```
**Symbols:**

```
ffffffff810bc720-ffffffff810bc846: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c3df0)
Location: kernel/sched/cputime.c:590
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810c3df0-ffffffff810c3ef9: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810cd0b0)
Location: kernel/sched/cputime.c:590
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810cd0b0-ffffffff810cd1b9: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d54a0)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810d54a0-ffffffff810d55aa: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810dfa60)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810dfa60-ffffffff810dfb6a: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7db0)
Location: kernel/sched/cputime.c:586
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810e7db0-ffffffff810e7eb8: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e544d)
Location: kernel/sched/cputime.c:540
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810e5aa0-ffffffff810e5b58: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e73fd)
Location: kernel/sched/cputime.c:540
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810e7a60-ffffffff810e7b18: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810fea0d)
Location: kernel/sched/cputime.c:540
Inline: True
Inline callers:
  - kernel/sched/cputime.c:task_cputime_adjusted
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810ff0f0-ffffffff810ff1a8: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f826)
Location: kernel/sched/cputime.c:539
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
Direct callers:
  - kernel/sched/build_policy.c:thread_group_cputime_adjusted
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81139a10-ffffffff81139adc: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811598c6)
Location: kernel/sched/cputime.c:554
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
Direct callers:
  - kernel/sched/build_policy.c:thread_group_cputime_adjusted
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff81164200-ffffffff811642cc: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81169ad6)
Location: kernel/sched/cputime.c:558
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:task_cputime_adjusted
Direct callers:
  - kernel/sched/build_policy.c:thread_group_cputime_adjusted
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff811749e0-ffffffff81174aac: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811822f0)
Location: kernel/sched/cputime.c:558
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:thread_group_cputime_adjusted
  - kernel/sched/build_policy.c:task_cputime_adjusted
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff811822f0-ffffffff811823bc: cputime_adjust (STB_GLOBAL)
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
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013f470)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffff80001013f470-ffff80001013f614: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038f404)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
c038f404-c038f62c: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018e540)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
c00000000018e540-c00000000018e6c8: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000eda44)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffe0000eda44-ffffffe0000edb42: cputime_adjust (STB_GLOBAL)
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
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d9c50)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810d9c50-ffffffff810d9d5a: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c86d0)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810c86d0-ffffffff810c87da: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5f90)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810d5f90-ffffffff810d609a: cputime_adjust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cputime_adjust(struct task_cputime *curr, struct prev_cputime *prev, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e18a0)
Location: kernel/sched/cputime.c:591
Inline: False
Direct callers:
  - kernel/sched/cputime.c:thread_group_cputime_adjusted
  - kernel/sched/cputime.c:task_cputime_adjusted
  - kernel/cgroup/rstat.c:cgroup_base_stat_cputime_show
```
**Symbols:**

```
ffffffff810e18a0-ffffffff810e19aa: cputime_adjust (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cputime_t *ut</code> ➡️ <code>u64 *ut</code>
</li>
<li>
<b>Param type changed. </b>
<code>cputime_t *st</code> ➡️ <code>u64 *st</code>
</li>
</ul>
</details>
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
