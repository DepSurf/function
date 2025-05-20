# Function: <code>task_numa_placement</code>

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
In kernel/sched/fair.c (ffffffff810ba6b2)
Location: kernel/sched/fair.c:1826
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810bdb1d)
Location: kernel/sched/fair.c:1939
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810c3061)
Location: kernel/sched/fair.c:2071
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810bde62)
Location: kernel/sched/fair.c:2067
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810c5b52)
Location: kernel/sched/fair.c:2119
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810cd7c9)
Location: kernel/sched/fair.c:2147
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810d608d)
Location: kernel/sched/fair.c:2096
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
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8940)
Location: kernel/sched/fair.c:2165
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810d8940-ffffffff810d8ec7: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3240)
Location: kernel/sched/fair.c:2123
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810e3240-ffffffff810e37c7: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec7b0)
Location: kernel/sched/fair.c:2352
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810ec7b0-ffffffff810ecc8c: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea5b0)
Location: kernel/sched/fair.c:2366
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810ea5b0-ffffffff810eaa8c: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810edf60)
Location: kernel/sched/fair.c:2363
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810edf60-ffffffff810ee523: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81104fb0)
Location: kernel/sched/fair.c:2352
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81104fb0-ffffffff81105583: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111ee30)
Location: kernel/sched/fair.c:2357
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff8111ee30-ffffffff8111f37d: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811481d0)
Location: kernel/sched/fair.c:2552
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff811481d0-ffffffff811486fd: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81158080)
Location: kernel/sched/fair.c:2552
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81158080-ffffffff8115859a: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811642d0)
Location: kernel/sched/fair.c:2793
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff811642d0-ffffffff8116476a: task_numa_placement (STB_LOCAL)
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
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101477d0)
Location: kernel/sched/fair.c:2123
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffff8000101477d0-ffff800010147fcc: task_numa_placement (STB_LOCAL)
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
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000193690)
Location: kernel/sched/fair.c:2123
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
c000000000193690-c0000000001941dc: task_numa_placement (STB_LOCAL)
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
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd3f0)
Location: kernel/sched/fair.c:2123
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810dd3f0-ffffffff810dd977: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cc400)
Location: kernel/sched/fair.c:2123
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810cc400-ffffffff810cc981: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d9770)
Location: kernel/sched/fair.c:2123
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810d9770-ffffffff810d9cf7: task_numa_placement (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_numa_placement(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e51a0)
Location: kernel/sched/fair.c:2123
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810e51a0-ffffffff810e571e: task_numa_placement (STB_LOCAL)
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
