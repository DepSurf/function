# Function: <code>ttwu_do_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aae50)
Location: kernel/sched/core.c:1717
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810aae50-ffffffff810aaf2e: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ada90)
Location: kernel/sched/core.c:1682
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810ada90-ffffffff810adb61: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3b90)
Location: kernel/sched/core.c:1692
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810b3b90-ffffffff810b3c62: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afaf0)
Location: kernel/sched/core.c:1654
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810afaf0-ffffffff810afc2b: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6ec0)
Location: kernel/sched/core.c:1673
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810b6ec0-ffffffff810b7007: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bea20)
Location: kernel/sched/core.c:1669
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810bea20-ffffffff810beb60: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7cc0)
Location: kernel/sched/core.c:1667
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810c7cc0-ffffffff810c7e00: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf030)
Location: kernel/sched/core.c:2097
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810cf030-ffffffff810cf179: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8df0)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810d8df0-ffffffff810d8f39: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e24d0)
Location: kernel/sched/core.c:2281
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810e24d0-ffffffff810e261d: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df890)
Location: kernel/sched/core.c:2936
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810df890-ffffffff810df9c8: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1680)
Location: kernel/sched/core.c:2957
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810e1680-ffffffff810e17b4: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3521
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810f77b0-ffffffff810f7910: ttwu_do_wakeup (STB_LOCAL)
ffffffff81ca5d61-ffffffff81ca5d76: ttwu_do_wakeup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3620
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff811139d0-ffffffff81113b68: ttwu_do_wakeup (STB_LOCAL)
ffffffff81e5569e-ffffffff81e556b3: ttwu_do_wakeup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3680
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff8113aba0-ffffffff8113ad38: ttwu_do_wakeup (STB_LOCAL)
ffffffff82056b10-ffffffff82056b25: ttwu_do_wakeup.cold (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff81151022)
Location: kernel/sched/core.c:3749
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
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
In kernel/sched/core.c (ffffffff8115ce22)
Location: kernel/sched/core.c:3768
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
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
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010139088)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffff800010139088-ffff8000101391e8: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03883ec)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
c03883ec-c03885b4: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000185760)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
c000000000185760-c000000000185928: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8dfc)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffe0000e8dfc-ffffffe0000e8f42: ttwu_do_wakeup (STB_LOCAL)
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
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d32c0)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810d32c0-ffffffff810d3409: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c18f0)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810c18f0-ffffffff810c1a39: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d09a0)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810d09a0-ffffffff810d0ae9: ttwu_do_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ttwu_do_wakeup(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810daa40)
Location: kernel/sched/core.c:2217
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:ttwu_do_activate
```
**Symbols:**

```
ffffffff810daa40-ffffffff810daba2: ttwu_do_wakeup (STB_LOCAL)
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
<code>struct pin_cookie cookie</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_flags *rf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pin_cookie cookie</code>
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
