# Function: <code>wake_affine</code>

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
In kernel/sched/fair.c (ffffffff810b37be)
Location: kernel/sched/fair.c:4677
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810b6409)
Location: kernel/sched/fair.c:5094
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810c50d8)
Location: kernel/sched/fair.c:5324
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810b7fda)
Location: kernel/sched/fair.c:5348
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810bf12c)
Location: kernel/sched/fair.c:5747
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810c77a5)
Location: kernel/sched/fair.c:5962
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810cff0b)
Location: kernel/sched/fair.c:5702
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810d7f87)
Location: kernel/sched/fair.c:5576
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810e2705)
Location: kernel/sched/fair.c:5522
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea570)
Location: kernel/sched/fair.c:5841
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810ea570-ffffffff810ea6b8: wake_affine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8340)
Location: kernel/sched/fair.c:5890
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810e8340-ffffffff810e8480: wake_affine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8be0)
Location: kernel/sched/fair.c:5953
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810e8be0-ffffffff810e8dfb: wake_affine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811002c0)
Location: kernel/sched/fair.c:5999
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff811002c0-ffffffff811005cc: wake_affine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111b4b0)
Location: kernel/sched/fair.c:6056
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff8111b4b0-ffffffff8111b7ce: wake_affine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81142fb0)
Location: kernel/sched/fair.c:6431
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81142fb0-ffffffff811432ce: wake_affine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81152f70)
Location: kernel/sched/fair.c:6684
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81152f70-ffffffff811532a9: wake_affine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wake_affine(struct sched_domain *sd, struct task_struct *p, int this_cpu, int prev_cpu, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115ea50)
Location: kernel/sched/fair.c:7080
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff8115ea50-ffffffff8115ed89: wake_affine (STB_LOCAL)
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
In kernel/sched/fair.c (ffff8000101436b8)
Location: kernel/sched/fair.c:5522
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (c03964cc)
Location: kernel/sched/fair.c:5522
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
In kernel/sched/fair.c (c000000000191ba4)
Location: kernel/sched/fair.c:5522
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffe0000ef1dc)
Location: kernel/sched/fair.c:5522
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
In kernel/sched/fair.c (ffffffff810dc8b5)
Location: kernel/sched/fair.c:5522
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810cb8c5)
Location: kernel/sched/fair.c:5522
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810d8c35)
Location: kernel/sched/fair.c:5522
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff810e473f)
Location: kernel/sched/fair.c:5522
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
