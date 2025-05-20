# Function: <code>migrate_task_rq_dl</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c6150)
Location: kernel/sched/deadline.c:1559
Inline: True
```
**Symbols:**

```
ffffffff810c6150-ffffffff810c62cf: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cd3a0)
Location: kernel/sched/deadline.c:1552
Inline: True
```
**Symbols:**

```
ffffffff810cd3a0-ffffffff810cd50d: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d5240)
Location: kernel/sched/deadline.c:1611
Inline: True
```
**Symbols:**

```
ffffffff810d5240-ffffffff810d543e: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dedc0)
Location: kernel/sched/deadline.c:1610
Inline: True
```
**Symbols:**

```
ffffffff810dedc0-ffffffff810defbe: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e6b90)
Location: kernel/sched/deadline.c:1609
Inline: True
```
**Symbols:**

```
ffffffff810e6b90-ffffffff810e6d88: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f1d20)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
ffffffff810f1d20-ffffffff810f1f18: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb960)
Location: kernel/sched/deadline.c:1644
Inline: True
```
**Symbols:**

```
ffffffff810fb960-ffffffff810fbb7b: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f9e80)
Location: kernel/sched/deadline.c:1742
Inline: True
```
**Symbols:**

```
ffffffff810f9e80-ffffffff810fa09b: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fbd90)
Location: kernel/sched/deadline.c:1721
Inline: True
```
**Symbols:**

```
ffffffff810fbd90-ffffffff810fbfab: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (ffffffff811182bb)
Location: kernel/sched/deadline.c:1721
Inline: True
```
**Symbols:**

```
ffffffff81118290-ffffffff8111853f: migrate_task_rq_dl (STB_LOCAL)
ffffffff81ca6c5a-ffffffff81ca6cbd: migrate_task_rq_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1868
Inline: False
```
**Symbols:**

```
ffffffff81132000-ffffffff81132318: migrate_task_rq_dl (STB_LOCAL)
ffffffff81e56204-ffffffff81e5627c: migrate_task_rq_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1875
Inline: False
```
**Symbols:**

```
ffffffff8115c2d0-ffffffff8115c5e8: migrate_task_rq_dl (STB_LOCAL)
ffffffff8205740a-ffffffff82057482: migrate_task_rq_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1866
Inline: False
```
**Symbols:**

```
ffffffff8116c690-ffffffff8116c9ac: migrate_task_rq_dl (STB_LOCAL)
ffffffff820d5c7c-ffffffff820d5cf4: migrate_task_rq_dl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1948
Inline: False
```
**Symbols:**

```
ffffffff81179f20-ffffffff8117a23c: migrate_task_rq_dl (STB_LOCAL)
ffffffff821b0d44-ffffffff821b0dbc: migrate_task_rq_dl.cold (STB_LOCAL)
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
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010154150)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
ffff800010154150-ffff8000101543b8: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a0b30)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
c03a0b30-c03a0e18: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a7ee0)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
c0000000001a7ee0-c0000000001a81ec: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fab44)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
ffffffe0000fab44-ffffffe0000facf8: migrate_task_rq_dl (STB_LOCAL)
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
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb120)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
ffffffff810eb120-ffffffff810eb318: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810db140)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
ffffffff810db140-ffffffff810db338: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e8250)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
ffffffff810e8250-ffffffff810e8448: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void migrate_task_rq_dl(struct task_struct *p, int new_cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f34c0)
Location: kernel/sched/deadline.c:1642
Inline: True
```
**Symbols:**

```
ffffffff810f34c0-ffffffff810f36b6: migrate_task_rq_dl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int new_cpu</code>
</li>
</ul>
</details>
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
