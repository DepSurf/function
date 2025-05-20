# Function: <code>select_idle_sibling</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b3200)
Location: kernel/sched/fair.c:4853
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b3200-ffffffff810b3313: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b5e60)
Location: kernel/sched/fair.c:5270
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b5e60-ffffffff810b5f66: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd500)
Location: kernel/sched/fair.c:5789
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810bd500-ffffffff810bd89e: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b73a0)
Location: kernel/sched/fair.c:5745
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b73a0-ffffffff810b77d9: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be8d0)
Location: kernel/sched/fair.c:6191
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810be8d0-ffffffff810becd3: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6a20)
Location: kernel/sched/fair.c:6423
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810c6a20-ffffffff810c6e75: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cef90)
Location: kernel/sched/fair.c:6164
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810cef90-ffffffff810cf366: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7870)
Location: kernel/sched/fair.c:6030
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810d7870-ffffffff810d7c3b: select_idle_sibling.part.0 (STB_LOCAL)
ffffffff810d7c40-ffffffff810d7ca5: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1e80)
Location: kernel/sched/fair.c:5990
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810e1e80-ffffffff810e23b1: select_idle_sibling.part.0 (STB_LOCAL)
ffffffff810e23c0-ffffffff810e2421: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eecb0)
Location: kernel/sched/fair.c:6191
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810eecb0-ffffffff810eeec4: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ecb00)
Location: kernel/sched/fair.c:6250
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810ecb00-ffffffff810ece62: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebfe0)
Location: kernel/sched/fair.c:6332
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810ebfe0-ffffffff810ec50c: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81104400)
Location: kernel/sched/fair.c:6400
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81104400-ffffffff81104c20: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81121880)
Location: kernel/sched/fair.c:6469
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81121880-ffffffff811220dd: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114d3b0)
Location: kernel/sched/fair.c:6845
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff8114d3b0-ffffffff8114de8c: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115b450)
Location: kernel/sched/fair.c:7119
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff8115b450-ffffffff8115bdef: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81166e50)
Location: kernel/sched/fair.c:7491
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff81166e50-ffffffff811676ce: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffff800010142d78)
Location: kernel/sched/fair.c:5990
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffff800010142d78-ffff8000101432f4: select_idle_sibling.part.0 (STB_LOCAL)
ffff8000101432f8-ffff800010143388: select_idle_sibling (STB_LOCAL)
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
In kernel/sched/fair.c (c03961ac)
Location: kernel/sched/fair.c:5990
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_task_rq_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (c000000000190f40)
Location: kernel/sched/fair.c:5990
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
c000000000190f40-c000000000191648: select_idle_sibling.part.0 (STB_LOCAL)
c000000000191650-c000000000191714: select_idle_sibling (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffe0000ef278)
Location: kernel/sched/fair.c:5990
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dc030)
Location: kernel/sched/fair.c:5990
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810dc030-ffffffff810dc561: select_idle_sibling.part.0 (STB_LOCAL)
ffffffff810dc570-ffffffff810dc5d1: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cb040)
Location: kernel/sched/fair.c:5990
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810cb040-ffffffff810cb571: select_idle_sibling.part.0 (STB_LOCAL)
ffffffff810cb580-ffffffff810cb5e1: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d83b0)
Location: kernel/sched/fair.c:5990
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810d83b0-ffffffff810d88e1: select_idle_sibling.part.0 (STB_LOCAL)
ffffffff810d88f0-ffffffff810d8951: select_idle_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_idle_sibling(struct task_struct *p, int prev, int target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3e50)
Location: kernel/sched/fair.c:5990
Inline: True
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810e3e50-ffffffff810e4381: select_idle_sibling.part.0 (STB_LOCAL)
ffffffff810e4390-ffffffff810e43f1: select_idle_sibling (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int prev</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, target</code> ➡️ <code>p, prev, target</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
