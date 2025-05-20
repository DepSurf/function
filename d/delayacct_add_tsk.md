# Function: <code>delayacct_add_tsk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8113e727)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81147297)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81151137)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811537b8)
Location: include/linux/delayacct.h:132
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8115ffb8)
Location: include/linux/delayacct.h:132
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8116eee8)
Location: include/linux/delayacct.h:132
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8117c9e8)
Location: include/linux/delayacct.h:139
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811898a0)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811957e3)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811aab67)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
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
In kernel/taskstats.c (ffffffff811a8117)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a8b6a)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff811d1640)
Location: kernel/delayacct.c:118
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff811d1640-ffffffff811d17b6: delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81205bf0)
Location: kernel/delayacct.c:129
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff81205bf0-ffffffff81205dd2: delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8124ddc0)
Location: kernel/delayacct.c:129
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff8124ddc0-ffffffff8124dfa2: delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff81265120)
Location: kernel/delayacct.c:129
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff81265120-ffffffff8126533b: delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int delayacct_add_tsk(struct taskstats *d, struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/delayacct.c (ffffffff8127ef40)
Location: kernel/delayacct.c:129
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_tgid
  - kernel/taskstats.c:fill_stats
```
**Symbols:**

```
ffffffff8127ef40-ffffffff8127f1be: delayacct_add_tsk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffff80001020d9f0)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c044c468)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c00000000028bb00)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffe00016e99e)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118de03)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81180f13)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118bbd3)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81199550)
Location: include/linux/delayacct.h:129
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
