# Function: <code>task_numa_migrate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b5d20)
Location: kernel/sched/fair.c:1448
Inline: False
Direct callers:
  - kernel/sched/fair.c:numa_migrate_preferred
```
**Symbols:**

```
ffffffff810b5d20-ffffffff810b66ce: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b8310)
Location: kernel/sched/fair.c:1565
Inline: False
Direct callers:
  - kernel/sched/fair.c:numa_migrate_preferred
```
**Symbols:**

```
ffffffff810b8310-ffffffff810b8c5a: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810beee0)
Location: kernel/sched/fair.c:1697
Inline: False
Direct callers:
  - kernel/sched/fair.c:numa_migrate_preferred
```
**Symbols:**

```
ffffffff810beee0-ffffffff810bf824: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b96c0)
Location: kernel/sched/fair.c:1693
Inline: False
Direct callers:
  - kernel/sched/fair.c:numa_migrate_preferred
```
**Symbols:**

```
ffffffff810b96c0-ffffffff810ba032: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1790)
Location: kernel/sched/fair.c:1734
Inline: False
Direct callers:
  - kernel/sched/fair.c:numa_migrate_preferred
```
**Symbols:**

```
ffffffff810c1790-ffffffff810c2106: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c86a0)
Location: kernel/sched/fair.c:1762
Inline: False
Direct callers:
  - kernel/sched/fair.c:numa_migrate_preferred
```
**Symbols:**

```
ffffffff810c86a0-ffffffff810c8fa6: task_numa_migrate (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810d65e0)
Location: kernel/sched/fair.c:1716
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d9780)
Location: kernel/sched/fair.c:1779
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810d9780-ffffffff810d9fee: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3f00)
Location: kernel/sched/fair.c:1737
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810e3f00-ffffffff810e476e: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810efc00)
Location: kernel/sched/fair.c:1964
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810efc00-ffffffff810f05f2: task_numa_migrate.isra.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810edc10)
Location: kernel/sched/fair.c:1978
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810edc10-ffffffff810ee5e7: task_numa_migrate.isra.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810efc40)
Location: kernel/sched/fair.c:1975
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810efc40-ffffffff810f0615: task_numa_migrate.isra.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff81108620)
Location: kernel/sched/fair.c:1964
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81108620-ffffffff81109094: task_numa_migrate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff81123590)
Location: kernel/sched/fair.c:1967
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81123590-ffffffff81124047: task_numa_migrate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114b520)
Location: kernel/sched/fair.c:2162
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff8114b520-ffffffff8114bfd5: task_numa_migrate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115d780)
Location: kernel/sched/fair.c:2162
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff8115d780-ffffffff8115e217: task_numa_migrate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff81168aa0)
Location: kernel/sched/fair.c:2403
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81168aa0-ffffffff81169537: task_numa_migrate.isra.0 (STB_LOCAL)
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
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010143fd0)
Location: kernel/sched/fair.c:1737
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffff800010143fd0-ffff800010144808: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001941e0)
Location: kernel/sched/fair.c:1737
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
c0000000001941e0-c000000000194c18: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de0b0)
Location: kernel/sched/fair.c:1737
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810de0b0-ffffffff810de91e: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cd0c0)
Location: kernel/sched/fair.c:1737
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810cd0c0-ffffffff810cd92e: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810da430)
Location: kernel/sched/fair.c:1737
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810da430-ffffffff810dac9e: task_numa_migrate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int task_numa_migrate(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e5e60)
Location: kernel/sched/fair.c:1737
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810e5e60-ffffffff810e6720: task_numa_migrate (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
