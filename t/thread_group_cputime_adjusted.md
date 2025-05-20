# Function: <code>thread_group_cputime_adjusted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b1bd0)
Location: kernel/sched/cputime.c:658
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810b1bd0-ffffffff810b1c3f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b46f0)
Location: kernel/sched/cputime.c:682
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810b46f0-ffffffff810b475f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bacd0)
Location: kernel/sched/cputime.c:693
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810bacd0-ffffffff810bad3f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b5570)
Location: kernel/sched/cputime.c:672
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810b5570-ffffffff810b55df: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc8c0)
Location: kernel/sched/cputime.c:677
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810bc8c0-ffffffff810bc92f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c3f70)
Location: kernel/sched/cputime.c:673
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810c3f70-ffffffff810c3fdf: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810cd230)
Location: kernel/sched/cputime.c:673
Inline: False
Direct callers:
  - kernel/exit.c:wait_consider_task
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810cd230-ffffffff810cd29f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d5620)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810d5620-ffffffff810d568f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810dfbe0)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810dfbe0-ffffffff810dfc4f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7f30)
Location: kernel/sched/cputime.c:669
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e7f30-ffffffff810e7f9f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e5b60)
Location: kernel/sched/cputime.c:623
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e5b60-ffffffff810e5bcf: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7b20)
Location: kernel/sched/cputime.c:623
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e7b20-ffffffff810e7b8f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ff1b0)
Location: kernel/sched/cputime.c:623
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810ff1b0-ffffffff810ff21f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81139ae0)
Location: kernel/sched/cputime.c:623
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81139ae0-ffffffff81139b75: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811642e0)
Location: kernel/sched/cputime.c:638
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff811642e0-ffffffff81164375: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174ac0)
Location: kernel/sched/cputime.c:642
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81174ac0-ffffffff81174b55: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81182bc0)
Location: kernel/sched/cputime.c:642
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81182bc0-ffffffff81182c55: thread_group_cputime_adjusted (STB_GLOBAL)
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
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013f698)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffff80001013f698-ffff80001013f714: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038f6ac)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:__se_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c038f6ac-c038f728: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018e760)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c00000000018e760-c00000000018e7f0: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000edb9a)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:__se_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffe0000edb9a-ffffffe0000edbec: thread_group_cputime_adjusted (STB_GLOBAL)
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
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d9dd0)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810d9dd0-ffffffff810d9e3f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8d30)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810c8d30-ffffffff810c8d9f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d6110)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810d6110-ffffffff810d617f: thread_group_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void thread_group_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e1a20)
Location: kernel/sched/cputime.c:674
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/sys.c:getrusage
  - kernel/sys.c:do_sys_times
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e1a20-ffffffff810e1a8f: thread_group_cputime_adjusted (STB_GLOBAL)
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
