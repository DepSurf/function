# Function: <code>preempt_schedule_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff818205e0)
Location: kernel/sched/core.c:3246
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
  - kernel/sched/core.c:__cond_resched_lock
```
**Symbols:**

```
ffffffff818205e0-ffffffff81820606: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8189aa40)
Location: kernel/sched/core.c:3464
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff8189aa40-ffffffff8189aa66: preempt_schedule_common (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff818cf068)
Location: kernel/sched/core.c:3495
Inline: True
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
In kernel/sched/core.c (ffffffff819065c8)
Location: kernel/sched/core.c:3453
Inline: True
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
In kernel/sched/core.c (ffffffff8199065d)
Location: kernel/sched/core.c:3497
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff819ece90)
Location: kernel/sched/core.c:3607
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff819ece90-ffffffff819eceb0: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a280c0)
Location: kernel/sched/core.c:3591
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81a280c0-ffffffff81a280e0: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a98840)
Location: kernel/sched/core.c:4010
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81a98840-ffffffff81a98862: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ad0190)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81ad0190-ffffffff81ad01b2: preempt_schedule_common (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810e1ba4)
Location: kernel/sched/core.c:4445
Inline: True
Inline callers:
  - kernel/sched/core.c:_cond_resched
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
In kernel/sched/core.c (ffffffff810def84)
Location: kernel/sched/core.c:5215
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
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
In kernel/sched/core.c (ffffffff810e2084)
Location: kernel/sched/core.c:5291
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f8306)
Location: kernel/sched/core.c:6454
Inline: True
Inline callers:
  - kernel/sched/core.c:affine_move_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81f226c0)
Location: kernel/sched/core.c:6619
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched
  - kernel/sched/core.c:preempt_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820cce90)
Location: kernel/sched/core.c:6760
Inline: False
Direct callers:
  - kernel/sched/core.c:__cond_resched
  - kernel/sched/core.c:preempt_schedule
```
**Symbols:**

```
ffffffff820cce90-ffffffff820ccecb: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811495aa)
Location: kernel/sched/core.c:6861
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:preempt_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81154faa)
Location: kernel/sched/core.c:6886
Inline: True
Inline callers:
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:preempt_schedule
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
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010da1ef8)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffff800010da1ef8-ffff800010da1f24: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0e9a020)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
c0e9a020-c0e9a050: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000ee3290)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
c000000000ee3290-c000000000ee32d4: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0008c5636)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffe0008c5636-ffffffe0008c5658: preempt_schedule_common (STB_LOCAL)
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
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a6f000)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81a6f000-ffffffff81a6f022: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81a2b3c0)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81a2b3c0-ffffffff81a2b3e2: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81adb410)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81adb410-ffffffff81adb432: preempt_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void preempt_schedule_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ae7950)
Location: kernel/sched/core.c:4213
Inline: False
Direct callers:
  - kernel/sched/core.c:__cond_resched_lock
  - kernel/sched/core.c:preempt_schedule
```
**Symbols:**

```
ffffffff81ae7950-ffffffff81ae7980: preempt_schedule_common (STB_LOCAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
