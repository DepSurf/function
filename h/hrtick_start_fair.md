# Function: <code>hrtick_start_fair</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b3a20)
Location: kernel/sched/fair.c:4098
Inline: True
Direct callers:
  - kernel/sched/fair.c:hrtick_update
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810b3a20-ffffffff810b3ab1: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b66c0)
Location: kernel/sched/fair.c:4454
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810b66c0-ffffffff810b6754: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bbe50)
Location: kernel/sched/fair.c:4671
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810bbe50-ffffffff810bbefa: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b6470)
Location: kernel/sched/fair.c:4814
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810b6470-ffffffff810b6517: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd680)
Location: kernel/sched/fair.c:5153
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810bd680-ffffffff810bd72a: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c55f0)
Location: kernel/sched/fair.c:5331
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810c55f0-ffffffff810c569a: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce230)
Location: kernel/sched/fair.c:5037
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810ce230-ffffffff810ce2da: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6790)
Location: kernel/sched/fair.c:5186
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810d6790-ffffffff810d683a: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0e10)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810e0e10-ffffffff810e0eba: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9310)
Location: kernel/sched/fair.c:5377
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810e9310-ffffffff810e93ba: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e70c0)
Location: kernel/sched/fair.c:5420
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810e70c0-ffffffff810e716a: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8e00)
Location: kernel/sched/fair.c:5483
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810e8e00-ffffffff810e8ea9: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5517
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff81100750-ffffffff81100837: hrtick_start_fair (STB_LOCAL)
ffffffff81ca6274-ffffffff81ca6289: hrtick_start_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5564
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff81122830-ffffffff8112292f: hrtick_start_fair (STB_LOCAL)
ffffffff81e55cf0-ffffffff81e55d05: hrtick_start_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5958
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff8114a580-ffffffff8114a67f: hrtick_start_fair (STB_LOCAL)
ffffffff82056f51-ffffffff82056f66: hrtick_start_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:6210
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff8115abf0-ffffffff8115acef: hrtick_start_fair (STB_LOCAL)
ffffffff820d56ca-ffffffff820d56df: hrtick_start_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:6618
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff8115edd0-ffffffff8115ee9d: hrtick_start_fair (STB_LOCAL)
ffffffff821b0407-ffffffff821b041c: hrtick_start_fair.cold (STB_LOCAL)
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
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010140c90)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffff800010140c90-ffff800010140d74: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0390e8c)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
c0390e8c-c0390f80: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000190730)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
c000000000190730-c000000000190898: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000eedba)
Location: kernel/sched/fair.c:5117
Inline: False
```
**Symbols:**

```
ffffffe0000eedba-ffffffe0000eee88: hrtick_start_fair (STB_LOCAL)
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
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dafc0)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810dafc0-ffffffff810db06a: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9fd0)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810c9fd0-ffffffff810ca07a: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7340)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810d7340-ffffffff810d73ea: hrtick_start_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtick_start_fair(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2cf0)
Location: kernel/sched/fair.c:5117
Inline: False
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:hrtick_update
```
**Symbols:**

```
ffffffff810e2cf0-ffffffff810e2d9a: hrtick_start_fair (STB_LOCAL)
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
