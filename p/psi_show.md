# Function: <code>psi_show</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810efa60)
Location: kernel/sched/psi.c:697
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff810efa60-ffffffff810efb86: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6f10)
Location: kernel/sched/psi.c:939
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff810f6f10-ffffffff810f7062: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81102ca0)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff81102ca0-ffffffff81102df2: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d6c5)
Location: kernel/sched/psi.c:989
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8110d0f0-ffffffff8110d234: psi_show.part.0 (STB_LOCAL)
ffffffff8110dd00-ffffffff8110dd1b: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110a955)
Location: kernel/sched/psi.c:1005
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8110a0f0-ffffffff8110a234: psi_show.part.0 (STB_LOCAL)
ffffffff8110b050-ffffffff8110b06b: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110cbf0)
Location: kernel/sched/psi.c:1033
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8110cbf0-ffffffff8110cd8e: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112bc40)
Location: kernel/sched/psi.c:1048
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8112bc40-ffffffff8112be81: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114c400)
Location: kernel/sched/psi.c:1046
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_show
  - kernel/sched/build_utility.c:psi_memory_show
  - kernel/sched/build_utility.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8114c400-ffffffff8114c6a5: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117b100)
Location: kernel/sched/psi.c:1210
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_show
  - kernel/sched/build_utility.c:psi_memory_show
  - kernel/sched/build_utility.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8117b100-ffffffff8117b3aa: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118bc60)
Location: kernel/sched/psi.c:1233
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_show
  - kernel/sched/build_utility.c:psi_memory_show
  - kernel/sched/build_utility.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8118bc60-ffffffff8118bf09: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119a5c0)
Location: kernel/sched/psi.c:1225
Inline: True
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_show
  - kernel/sched/build_utility.c:psi_memory_show
  - kernel/sched/build_utility.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff8119a5c0-ffffffff8119a869: psi_show (STB_GLOBAL)
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
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167b28)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffff800010167b28-ffff800010167ca4: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (c03b3dec)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
c03b3dec-c03b4010: psi_show.part.0 (STB_LOCAL)
c03b4948-c03b4980: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bf9d0)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
c0000000001bf9d0-c0000000001bfba4: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffe0001093a4)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffe0001093a4-ffffffe0001094d8: psi_show.part.0 (STB_LOCAL)
ffffffe00010a080-ffffffe00010a0d8: psi_show (STB_GLOBAL)
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
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fbfb0)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff810fbfb0-ffffffff810fc102: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ec1c0)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff810ec1c0-ffffffff810ec312: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f9170)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff810f9170-ffffffff810f92c2: psi_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int psi_show(struct seq_file *m, struct psi_group *group, enum psi_res res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff811042b0)
Location: kernel/sched/psi.c:940
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_show
  - kernel/sched/psi.c:psi_memory_show
  - kernel/sched/psi.c:psi_io_show
  - kernel/cgroup/cgroup.c:cgroup_cpu_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_memory_pressure_show
  - kernel/cgroup/cgroup.c:cgroup_io_pressure_show
```
**Symbols:**

```
ffffffff811042b0-ffffffff81104402: psi_show (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
