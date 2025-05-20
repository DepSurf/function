# Function: <code>task_cputime_adjusted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b1670)
Location: kernel/sched/cputime.c:647
Inline: False
Direct callers:
  - kernel/sys.c:k_getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810b1670-ffffffff810b16dc: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b4100)
Location: kernel/sched/cputime.c:671
Inline: False
Direct callers:
  - kernel/sys.c:k_getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810b4100-ffffffff810b416c: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, cputime_t *ut, cputime_t *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810ba740)
Location: kernel/sched/cputime.c:682
Inline: False
Direct callers:
  - kernel/sys.c:k_getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810ba740-ffffffff810ba7ac: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810b4fc0)
Location: kernel/sched/cputime.c:661
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810b4fc0-ffffffff810b502c: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810bc850)
Location: kernel/sched/cputime.c:666
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810bc850-ffffffff810bc8bc: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c3f00)
Location: kernel/sched/cputime.c:662
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810c3f00-ffffffff810c3f6c: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810cd1c0)
Location: kernel/sched/cputime.c:662
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810cd1c0-ffffffff810cd22c: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d55b0)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810d55b0-ffffffff810d561c: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810dfb70)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810dfb70-ffffffff810dfbdc: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e7ec0)
Location: kernel/sched/cputime.c:658
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e7ec0-ffffffff810e7f2a: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e5410)
Location: kernel/sched/cputime.c:612
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e5410-ffffffff810e54ee: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e73c0)
Location: kernel/sched/cputime.c:612
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e73c0-ffffffff810e749e: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810fe9d0)
Location: kernel/sched/cputime.c:612
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810fe9d0-ffffffff810feaae: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f7e0)
Location: kernel/sched/cputime.c:611
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8112f7e0-ffffffff8112f8de: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81159880)
Location: kernel/sched/cputime.c:626
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81159880-ffffffff8115997e: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81169a90)
Location: kernel/sched/cputime.c:630
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81169a90-ffffffff81169b8e: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81182c70)
Location: kernel/sched/cputime.c:630
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81182c70-ffffffff81182d17: task_cputime_adjusted (STB_GLOBAL)
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
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffff80001013f618)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffff80001013f618-ffff80001013f698: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c038f62c)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c038f62c-c038f6ac: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (c00000000018e6d0)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c00000000018e6d0-c00000000018e754: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffe0000edb42)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffe0000edb42-ffffffe0000edb9a: task_cputime_adjusted (STB_GLOBAL)
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
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d9d60)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810d9d60-ffffffff810d9dcc: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8da0)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810c8da0-ffffffff810c8e27: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810d60a0)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810d60a0-ffffffff810d610c: task_cputime_adjusted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_cputime_adjusted(struct task_struct *p, u64 *ut, u64 *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810e19b0)
Location: kernel/sched/cputime.c:663
Inline: False
Direct callers:
  - kernel/sys.c:getrusage
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810e19b0-ffffffff810e1a1c: task_cputime_adjusted (STB_GLOBAL)
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
