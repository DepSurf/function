# Function: <code>find_idlest_cpu</code>

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
In kernel/sched/fair.c (ffffffff810b342a)
Location: kernel/sched/fair.c:4805
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
In kernel/sched/fair.c (ffffffff810b60a8)
Location: kernel/sched/fair.c:5222
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
In kernel/sched/fair.c (ffffffff810c4b22)
Location: kernel/sched/fair.c:5533
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
In kernel/sched/fair.c (ffffffff810b79bc)
Location: kernel/sched/fair.c:5515
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
In kernel/sched/fair.c (ffffffff810bee91)
Location: kernel/sched/fair.c:5963
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
In kernel/sched/fair.c (ffffffff810c7172)
Location: kernel/sched/fair.c:6188
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
In kernel/sched/fair.c (ffffffff810cf85e)
Location: kernel/sched/fair.c:5928
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6dc0)
Location: kernel/sched/fair.c:5793
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810d6dc0-ffffffff810d7428: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e13a0)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810e13a0-ffffffff810e1a40: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb670)
Location: kernel/sched/fair.c:5920
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810eb670-ffffffff810eb8eb: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9490)
Location: kernel/sched/fair.c:5969
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810e9490-ffffffff810e970b: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb0b0)
Location: kernel/sched/fair.c:6032
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810eb0b0-ffffffff810eb32d: find_idlest_cpu (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff81104e1c)
Location: kernel/sched/fair.c:6082
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff81122334)
Location: kernel/sched/fair.c:6139
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114e0f4)
Location: kernel/sched/fair.c:6514
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff8115c069)
Location: kernel/sched/fair.c:6767
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
In kernel/sched/fair.c (ffffffff81167974)
Location: kernel/sched/fair.c:7163
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
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
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010141950)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffff800010141950-ffff800010141f68: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0390780)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
c0390780-c0390ddc: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000018fea0)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
c00000000018fea0-c000000000190640: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000ee7e8)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffe0000ee7e8-ffffffe0000eed22: find_idlest_cpu (STB_LOCAL)
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
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db550)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810db550-ffffffff810dbbf0: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ca560)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810ca560-ffffffff810cac00: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d78d0)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810d78d0-ffffffff810d7f70: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int find_idlest_cpu(struct sched_domain *sd, struct task_struct *p, int cpu, int prev_cpu, int sd_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3370)
Location: kernel/sched/fair.c:5748
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810e3370-ffffffff810e3a10: find_idlest_cpu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
