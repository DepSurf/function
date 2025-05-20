# Function: <code>select_idle_cpu</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd64e)
Location: kernel/sched/fair.c:5748
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
In kernel/sched/fair.c (ffffffff810b7538)
Location: kernel/sched/fair.c:5693
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
In kernel/sched/fair.c (ffffffff810bea46)
Location: kernel/sched/fair.c:6139
Inline: True
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
In kernel/sched/fair.c (ffffffff810c6bc9)
Location: kernel/sched/fair.c:6371
Inline: True
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
In kernel/sched/fair.c (ffffffff810cf139)
Location: kernel/sched/fair.c:6112
Inline: True
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
In kernel/sched/fair.c (ffffffff810d79d5)
Location: kernel/sched/fair.c:5977
Inline: True
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
In kernel/sched/fair.c (ffffffff810e1ff1)
Location: kernel/sched/fair.c:5934
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9eb0)
Location: kernel/sched/fair.c:6106
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff810e9eb0-ffffffff810ea0f4: select_idle_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e7c10)
Location: kernel/sched/fair.c:6157
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff810e7c10-ffffffff810e7e54: select_idle_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, bool has_idle_core, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebd10)
Location: kernel/sched/fair.c:6228
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff810ebd10-ffffffff810ebfd8: select_idle_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, bool has_idle_core, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81103990)
Location: kernel/sched/fair.c:6279
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff81103990-ffffffff81103d8b: select_idle_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, bool has_idle_core, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111f860)
Location: kernel/sched/fair.c:6336
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff8111f860-ffffffff8111fc8d: select_idle_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, bool has_idle_core, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811458f0)
Location: kernel/sched/fair.c:6707
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff811458f0-ffffffff81145d91: select_idle_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, bool has_idle_core, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811566b0)
Location: kernel/sched/fair.c:6960
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff811566b0-ffffffff81156b6a: select_idle_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int select_idle_cpu(struct task_struct *p, struct sched_domain *sd, bool has_idle_core, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811636b0)
Location: kernel/sched/fair.c:7356
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff811636b0-ffffffff81163c60: select_idle_cpu (STB_LOCAL)
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
In kernel/sched/fair.c (ffff800010142f28)
Location: kernel/sched/fair.c:5934
Inline: True
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
In kernel/sched/fair.c (c0396244)
Location: kernel/sched/fair.c:5934
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (c00000000019114c)
Location: kernel/sched/fair.c:5934
Inline: True
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
In kernel/sched/fair.c (ffffffe0000ef2fa)
Location: kernel/sched/fair.c:5934
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810dc1a1)
Location: kernel/sched/fair.c:5934
Inline: True
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
In kernel/sched/fair.c (ffffffff810cb1b1)
Location: kernel/sched/fair.c:5934
Inline: True
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
In kernel/sched/fair.c (ffffffff810d8521)
Location: kernel/sched/fair.c:5934
Inline: True
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
In kernel/sched/fair.c (ffffffff810e3fc1)
Location: kernel/sched/fair.c:5934
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool has_idle_core</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, sd, target</code> ➡️ <code>p, sd, has_idle_core, target</code>
</li>
</ul>
</details>
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
