# Function: <code>select_task_rq_dl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c1950)
Location: kernel/sched/deadline.c:1047
Inline: True
```
**Symbols:**

```
ffffffff810c1950-ffffffff810c19fc: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c54b0)
Location: kernel/sched/deadline.c:1023
Inline: True
```
**Symbols:**

```
ffffffff810c54b0-ffffffff810c5557: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cb2a0)
Location: kernel/sched/deadline.c:1012
Inline: True
```
**Symbols:**

```
ffffffff810cb2a0-ffffffff810cb347: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c55e0)
Location: kernel/sched/deadline.c:1519
Inline: True
```
**Symbols:**

```
ffffffff810c55e0-ffffffff810c568a: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ccd20)
Location: kernel/sched/deadline.c:1512
Inline: True
```
**Symbols:**

```
ffffffff810ccd20-ffffffff810ccdca: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d4c60)
Location: kernel/sched/deadline.c:1571
Inline: True
```
**Symbols:**

```
ffffffff810d4c60-ffffffff810d4d10: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810de610)
Location: kernel/sched/deadline.c:1570
Inline: True
```
**Symbols:**

```
ffffffff810de610-ffffffff810de6c0: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e5690)
Location: kernel/sched/deadline.c:1569
Inline: True
```
**Symbols:**

```
ffffffff810e5690-ffffffff810e573e: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f0ab0)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
ffffffff810f0ab0-ffffffff810f0b5e: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa5e0)
Location: kernel/sched/deadline.c:1604
Inline: True
```
**Symbols:**

```
ffffffff810fa5e0-ffffffff810fa685: select_task_rq_dl.part.0 (STB_LOCAL)
ffffffff810fa690-ffffffff810fa6a8: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f8a30)
Location: kernel/sched/deadline.c:1692
Inline: True
```
**Symbols:**

```
ffffffff810f8a30-ffffffff810f8b23: select_task_rq_dl.part.0 (STB_LOCAL)
ffffffff810f8b30-ffffffff810f8b48: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa950)
Location: kernel/sched/deadline.c:1671
Inline: True
```
**Symbols:**

```
ffffffff810fa950-ffffffff810faa4a: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81115990)
Location: kernel/sched/deadline.c:1671
Inline: True
```
**Symbols:**

```
ffffffff81115990-ffffffff81115b11: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81134c40)
Location: kernel/sched/deadline.c:1818
Inline: True
```
**Symbols:**

```
ffffffff81134c40-ffffffff81134dc9: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115f190)
Location: kernel/sched/deadline.c:1827
Inline: True
```
**Symbols:**

```
ffffffff8115f190-ffffffff8115f2d2: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116f880)
Location: kernel/sched/deadline.c:1818
Inline: True
```
**Symbols:**

```
ffffffff8116f880-ffffffff8116f9c8: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117cdd0)
Location: kernel/sched/deadline.c:1900
Inline: True
```
**Symbols:**

```
ffffffff8117cdd0-ffffffff8117cf18: select_task_rq_dl (STB_LOCAL)
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
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010152798)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
ffff800010152798-ffff800010152868: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c039f640)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
c039f640-c039f740: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a5ee0)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
c0000000001a5ee0-c0000000001a6018: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fa3a0)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
ffffffe0000fa3a0-ffffffe0000fa460: select_task_rq_dl (STB_LOCAL)
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
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e9eb0)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
ffffffff810e9eb0-ffffffff810e9f5e: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d9e70)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
ffffffff810d9e70-ffffffff810d9f1e: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e6fe0)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
ffffffff810e6fe0-ffffffff810e708e: select_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int select_task_rq_dl(struct task_struct *p, int cpu, int sd_flag, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f1f80)
Location: kernel/sched/deadline.c:1602
Inline: True
```
**Symbols:**

```
ffffffff810f1f80-ffffffff810f204b: select_task_rq_dl (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sd_flag</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, cpu, sd_flag, flags</code> ➡️ <code>p, cpu, flags</code>
</li>
</ul>
</details>
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
