# Function: <code>__delayacct_add_tsk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8113df80)
Location: kernel/delayacct.c:83
Inline: False
Direct callers:
  - kernel/taskstats.c:fill_stats
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8113df80-ffffffff8113e0e8: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81146590)
Location: kernel/delayacct.c:83
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff81146590-ffffffff8114673b: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811503d0)
Location: kernel/delayacct.c:83
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff811503d0-ffffffff8115057b: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811529f0)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff811529f0-ffffffff81152b6c: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8115f210)
Location: kernel/delayacct.c:93
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff8115f210-ffffffff8115f38c: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8116e1c0)
Location: kernel/delayacct.c:94
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff8116e1c0-ffffffff8116e2fd: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8117bc00)
Location: kernel/delayacct.c:94
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff8117bc00-ffffffff8117bd6d: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81188a20)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff81188a20-ffffffff81188b8d: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81194960)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff81194960-ffffffff81194acd: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811a99c0)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff811a99c0-ffffffff811a9b2d: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811a6fe0)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff811a6fe0-ffffffff811a714d: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811a7b20)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff811a7b20-ffffffff811a7c8d: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
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
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffff80001020ca50)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffff80001020ca50-ffff80001020cc18: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (c044b3cc)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
c044b3cc-c044b694: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (c00000000028a6f0)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
c00000000028a6f0-c00000000028a8b4: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffe00016dd6a)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffe00016dd6a-ffffffe00016deae: __delayacct_add_tsk (STB_GLOBAL)
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
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8118cf80)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff8118cf80-ffffffff8118d0ed: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81180060)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff81180060-ffffffff81180210: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8118ad50)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff8118ad50-ffffffff8118aebd: __delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811986c0)
Location: kernel/delayacct.c:85
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff811986c0-ffffffff8119882d: __delayacct_add_tsk (STB_GLOBAL)
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
