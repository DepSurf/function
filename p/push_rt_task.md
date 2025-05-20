# Function: <code>push_rt_task</code>

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
In kernel/sched/rt.c (ffffffff810c09e0)
Location: kernel/sched/rt.c:1715
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
Direct callers:
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff810c09e0-ffffffff810c0c45: push_rt_task.part.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c473d)
Location: kernel/sched/rt.c:1778
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
Direct callers:
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff810c4470-ffffffff810c46d7: push_rt_task.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ca78d)
Location: kernel/sched/rt.c:1777
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
Direct callers:
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff810ca4d0-ffffffff810ca72f: push_rt_task.part.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c429f)
Location: kernel/sched/rt.c:1788
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_irq_work_func
Direct callers:
  - kernel/sched/rt.c:push_irq_work_func
```
**Symbols:**

```
ffffffff810c3fe0-ffffffff810c4236: push_rt_task.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cb9e0)
Location: kernel/sched/rt.c:1778
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810cb9e0-ffffffff810cbc14: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d4160)
Location: kernel/sched/rt.c:1789
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810d4160-ffffffff810d439a: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dd670)
Location: kernel/sched/rt.c:1802
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810dd670-ffffffff810dd8aa: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1802
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e4640-ffffffff810e48a0: push_rt_task (STB_LOCAL)
ffffffff810e531c-ffffffff810e5331: push_rt_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ef800)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810ef800-ffffffff810efa6f: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9260)
Location: kernel/sched/rt.c:1862
Inline: False
Direct callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810f9260-ffffffff810f944b: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f77a9)
Location: kernel/sched/rt.c:1864
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:rto_push_irq_work_func
Direct callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810f7450-ffffffff810f7725: push_rt_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f9cb9)
Location: kernel/sched/rt.c:1864
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:rto_push_irq_work_func
Direct callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810f9960-ffffffff810f9c39: push_rt_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff81112c09)
Location: kernel/sched/rt.c:1889
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:rto_push_irq_work_func
Direct callers:
  - kernel/sched/rt.c:task_woken_rt
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff81112870-ffffffff81112b8f: push_rt_task.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq, bool pull);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81130620)
Location: kernel/sched/rt.c:2054
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff81130620-ffffffff81130978: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq, bool pull);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115a710)
Location: kernel/sched/rt.c:2053
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff8115a710-ffffffff8115aa68: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq, bool pull);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116a920)
Location: kernel/sched/rt.c:2057
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff8116a920-ffffffff8116ac78: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq, bool pull);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81178000)
Location: kernel/sched/rt.c:2002
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff81178000-ffffffff81178376: push_rt_task (STB_LOCAL)
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
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010150a70)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffff800010150a70-ffff800010150e20: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039be5c)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
c039be5c-c039c15c: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a22f0)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
c0000000001a22f0-c0000000001a2784: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f9130)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffe0000f9130-ffffffe0000f9488: push_rt_task (STB_LOCAL)
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
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e90f0)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e90f0-ffffffff810e935f: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d8bc0)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810d8bc0-ffffffff810d8e2a: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e5d30)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e5d30-ffffffff810e5f9f: push_rt_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int push_rt_task(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0540)
Location: kernel/sched/rt.c:1792
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810f0540-ffffffff810f07ae: push_rt_task (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
