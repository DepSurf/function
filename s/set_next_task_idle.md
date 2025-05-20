# Function: <code>set_next_task_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810dfce0)
Location: kernel/sched/idle.c:388
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810dfce0-ffffffff810dfd0b: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e80c2)
Location: kernel/sched/idle.c:405
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810e8010-ffffffff810e8041: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e5ce2)
Location: kernel/sched/idle.c:430
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810e5c30-ffffffff810e5c61: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e7ca2)
Location: kernel/sched/idle.c:436
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810e7bf0-ffffffff810e7c21: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ff2a0)
Location: kernel/sched/idle.c:436
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810ff2a0-ffffffff810ff2de: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112f4e2)
Location: kernel/sched/idle.c:433
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_idle
  - kernel/sched/build_policy.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff8112e750-ffffffff8112e787: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811592a2)
Location: kernel/sched/idle.c:433
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_idle
  - kernel/sched/build_policy.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff81158700-ffffffff81158737: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81169562)
Location: kernel/sched/idle.c:412
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_idle
  - kernel/sched/build_policy.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff81168890-ffffffff811688c7: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81176722)
Location: kernel/sched/idle.c:443
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_idle
  - kernel/sched/build_policy.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff81175920-ffffffff81175957: set_next_task_idle (STB_LOCAL)
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
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff80001013f878)
Location: kernel/sched/idle.c:388
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffff80001013f878-ffff80001013f8c8: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c038f824)
Location: kernel/sched/idle.c:388
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
c038f7ac-c038f7e0: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c00000000018e960)
Location: kernel/sched/idle.c:388
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
c00000000018e960-c00000000018e9cc: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0000edd40)
Location: kernel/sched/idle.c:388
Inline: True
Inline callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffe0000edcc4-ffffffe0000edd08: set_next_task_idle (STB_LOCAL)
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
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d9ed0)
Location: kernel/sched/idle.c:388
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810d9ed0-ffffffff810d9efb: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c8ec0)
Location: kernel/sched/idle.c:388
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810c8ec0-ffffffff810c8eeb: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d6210)
Location: kernel/sched/idle.c:388
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810d6210-ffffffff810d623b: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_next_task_idle(struct rq *rq, struct task_struct *next, bool first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e1b20)
Location: kernel/sched/idle.c:388
Inline: False
Direct callers:
  - kernel/sched/idle.c:pick_next_task_idle
```
**Symbols:**

```
ffffffff810e1b20-ffffffff810e1b4b: set_next_task_idle (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
