# Function: <code>find_idlest_group</code>

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
In kernel/sched/fair.c (ffffffff810b3446)
Location: kernel/sched/fair.c:4748
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
In kernel/sched/fair.c (ffffffff810b60f0)
Location: kernel/sched/fair.c:5165
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
In kernel/sched/fair.c (ffffffff810c4b5c)
Location: kernel/sched/fair.c:5403
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
In kernel/sched/fair.c (ffffffff810b79e0)
Location: kernel/sched/fair.c:5385
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
In kernel/sched/fair.c (ffffffff810beed0)
Location: kernel/sched/fair.c:5783
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
In kernel/sched/fair.c (ffffffff810c71b8)
Location: kernel/sched/fair.c:5996
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
In kernel/sched/fair.c (ffffffff810cf8b2)
Location: kernel/sched/fair.c:5736
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
In kernel/sched/fair.c (ffffffff810d6e43)
Location: kernel/sched/fair.c:5610
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810e1423)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb330)
Location: kernel/sched/fair.c:8721
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810eb330-ffffffff810eb669: find_idlest_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9120)
Location: kernel/sched/fair.c:8815
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810e9120-ffffffff810e948d: find_idlest_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ead40)
Location: kernel/sched/fair.c:8882
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810ead40-ffffffff810eb0ad: find_idlest_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81102a30)
Location: kernel/sched/fair.c:9113
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81102a30-ffffffff81102fe2: find_idlest_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111dff0)
Location: kernel/sched/fair.c:9111
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff8111dff0-ffffffff8111e5f6: find_idlest_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811472a0)
Location: kernel/sched/fair.c:9628
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff811472a0-ffffffff8114798f: find_idlest_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81157130)
Location: kernel/sched/fair.c:9897
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81157130-ffffffff81157820: find_idlest_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sched_group *find_idlest_group(struct sched_domain *sd, struct task_struct *p, int this_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81162580)
Location: kernel/sched/fair.c:10315
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81162580-ffffffff81162c82: find_idlest_group (STB_LOCAL)
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
In kernel/sched/fair.c (ffff8000101419d8)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (c0390808)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (c00000000018ff70)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffe0000ee83a)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810db5d3)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810ca5e3)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810d7953)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
In kernel/sched/fair.c (ffffffff810e33f3)
Location: kernel/sched/fair.c:5556
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_cpu
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
