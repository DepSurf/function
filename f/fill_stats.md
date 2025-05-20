# Function: <code>fill_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8113e6e0)
Location: kernel/taskstats.c:169
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_user_cmd
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8113e6e0-ffffffff8113e794: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81146d10)
Location: kernel/taskstats.c:169
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffff81146d10-ffffffff81146dc4: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81150900)
Location: kernel/taskstats.c:168
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81150900-ffffffff811509b4: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81152f00)
Location: kernel/taskstats.c:169
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81152f00-ffffffff81152fb4: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8115f720)
Location: kernel/taskstats.c:169
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8115f720-ffffffff8115f7d4: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8116e4a0)
Location: kernel/taskstats.c:169
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8116e4a0-ffffffff8116e552: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8117bf70)
Location: kernel/taskstats.c:169
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8117bf70-ffffffff8117c022: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81188e00)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81188e00-ffffffff81188eb5: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81194d40)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81194d40-ffffffff81194df5: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811aa4d0)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_pid
```
**Symbols:**

```
ffffffff811aa4d0-ffffffff811aa585: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a7a80)
Location: kernel/taskstats.c:155
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:fill_stats_for_pid
```
**Symbols:**

```
ffffffff811a7a80-ffffffff811a7b35: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811a8460)
Location: kernel/taskstats.c:155
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff811a8460-ffffffff811a8515: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff811d1aa0)
Location: kernel/taskstats.c:155
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff811d1aa0-ffffffff811d1b41: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81206220)
Location: kernel/taskstats.c:174
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff81206220-ffffffff81206346: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8124e510)
Location: kernel/taskstats.c:174
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff8124e510-ffffffff8124e636: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff812658c0)
Location: kernel/taskstats.c:174
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff812658c0-ffffffff812659ec: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8127f740)
Location: kernel/taskstats.c:174
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:cmd_attr_pid
```
**Symbols:**

```
ffffffff8127f740-ffffffff8127f86c: fill_stats (STB_LOCAL)
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
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffff80001020d218)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffff80001020d218-ffff80001020d2b8: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c044bba4)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
c044bba4-c044bc4c: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (c00000000028af90)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
c00000000028af90-c00000000028b070: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffe00016e34c)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
  - kernel/taskstats.c:taskstats_user_cmd
```
**Symbols:**

```
ffffffe00016e34c-ffffffe00016e3e0: fill_stats (STB_LOCAL)
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
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118d360)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8118d360-ffffffff8118d415: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81180480)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81180480-ffffffff81180535: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff8118b130)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff8118b130-ffffffff8118b1e5: fill_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fill_stats(struct user_namespace *user_ns, struct pid_namespace *pid_ns, struct task_struct *tsk, struct taskstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/taskstats.c (ffffffff81198aa0)
Location: kernel/taskstats.c:159
Inline: False
Direct callers:
  - kernel/taskstats.c:taskstats_exit
```
**Symbols:**

```
ffffffff81198aa0-ffffffff81198b55: fill_stats (STB_LOCAL)
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
