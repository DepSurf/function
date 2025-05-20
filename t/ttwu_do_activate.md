# Function: <code>ttwu_do_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810aaf70)
Location: kernel/sched/core.c:1749
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810aaf70-ffffffff810aafd2: ttwu_do_activate.constprop.89 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810adb70)
Location: kernel/sched/core.c:1715
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810adb70-ffffffff810adbe6: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct pin_cookie cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3c70)
Location: kernel/sched/core.c:1725
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810b3c70-ffffffff810b3ce6: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afc30)
Location: kernel/sched/core.c:1687
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810afc30-ffffffff810afcb3: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b7010)
Location: kernel/sched/core.c:1706
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810b7010-ffffffff810b7093: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810beb60)
Location: kernel/sched/core.c:1702
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810beb60-ffffffff810bebe2: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7e00)
Location: kernel/sched/core.c:1700
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810c7e00-ffffffff810c7e82: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf180)
Location: kernel/sched/core.c:2130
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810cf180-ffffffff810cf1e5: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8f40)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810d8f40-ffffffff810d8fa5: ttwu_do_activate (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810e3588)
Location: kernel/sched/core.c:2314
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df9d0)
Location: kernel/sched/core.c:2969
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810df9d0-ffffffff810dfa9e: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e17c0)
Location: kernel/sched/core.c:2990
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810e17c0-ffffffff810e187e: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f7910)
Location: kernel/sched/core.c:3557
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810f7910-ffffffff810f79fc: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81113b70)
Location: kernel/sched/core.c:3656
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff81113b70-ffffffff81113c53: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ad50)
Location: kernel/sched/core.c:3716
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff8113ad50-ffffffff8113ae33: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3756
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff811505f0-ffffffff8115087a: ttwu_do_activate (STB_LOCAL)
ffffffff820d537f-ffffffff820d5394: ttwu_do_activate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:3775
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff8115c4b0-ffffffff8115c710: ttwu_do_activate (STB_LOCAL)
ffffffff821b02f7-ffffffff821b030c: ttwu_do_activate.cold (STB_LOCAL)
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
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101391e8)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffff8000101391e8-ffff800010139264: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03885b4)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
c03885b4-c0388618: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000185930)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
c000000000185930-c0000000001859b0: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8f42)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffe0000e8f42-ffffffe0000e8fb2: ttwu_do_activate (STB_LOCAL)
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
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3410)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810d3410-ffffffff810d3475: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1a40)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810c1a40-ffffffff810c1aa5: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0af0)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810d0af0-ffffffff810d0b55: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ttwu_do_activate(struct rq *rq, struct task_struct *p, int wake_flags, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dabb0)
Location: kernel/sched/core.c:2250
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:sched_ttwu_pending
```
**Symbols:**

```
ffffffff810dabb0-ffffffff810dac15: ttwu_do_activate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
