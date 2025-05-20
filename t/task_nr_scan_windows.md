# Function: <code>task_nr_scan_windows</code>

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
In kernel/sched/fair.c (ffffffff810b1de2)
Location: kernel/sched/fair.c:819
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_scan_min
  - kernel/sched/fair.c:task_scan_max
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4900)
Location: kernel/sched/fair.c:953
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810b4900-ffffffff810b496c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810baee0)
Location: kernel/sched/fair.c:1077
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810baee0-ffffffff810baf4c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b5790)
Location: kernel/sched/fair.c:1074
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810b5790-ffffffff810b57fc: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bcab0)
Location: kernel/sched/fair.c:1077
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810bcab0-ffffffff810bcb1c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c47f0)
Location: kernel/sched/fair.c:1064
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810c47f0-ffffffff810c485c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cda50)
Location: kernel/sched/fair.c:1060
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810cda50-ffffffff810cdabc: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5d60)
Location: kernel/sched/fair.c:1107
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810d5d60-ffffffff810d5dcc: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0360)
Location: kernel/sched/fair.c:1106
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810e0360-ffffffff810e03cc: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e86c0)
Location: kernel/sched/fair.c:1117
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810e86c0-ffffffff810e872c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e62d0)
Location: kernel/sched/fair.c:1124
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810e62d0-ffffffff810e633c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e82b0)
Location: kernel/sched/fair.c:1121
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810e82b0-ffffffff810e8317: task_nr_scan_windows (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff811008e0)
Location: kernel/sched/fair.c:1110
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff811008e0-ffffffff81100940: task_nr_scan_windows.isra.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff8111b980)
Location: kernel/sched/fair.c:1112
Inline: True
Direct callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff8111b980-ffffffff8111b9ec: task_nr_scan_windows.isra.0 (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff811434e0)
Location: kernel/sched/fair.c:1151
Inline: True
Direct callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff811434e0-ffffffff8114354c: task_nr_scan_windows.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811525f0)
Location: kernel/sched/fair.c:1168
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff811525f0-ffffffff81152663: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115e5a0)
Location: kernel/sched/fair.c:1409
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff8115e5a0-ffffffff8115e613: task_nr_scan_windows (STB_LOCAL)
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
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010140160)
Location: kernel/sched/fair.c:1106
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffff800010140160-ffff8000101401d8: task_nr_scan_windows (STB_LOCAL)
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
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000018f340)
Location: kernel/sched/fair.c:1106
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
c00000000018f340-c00000000018f3bc: task_nr_scan_windows (STB_LOCAL)
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
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810da510)
Location: kernel/sched/fair.c:1106
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810da510-ffffffff810da57c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9520)
Location: kernel/sched/fair.c:1106
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810c9520-ffffffff810c958c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6890)
Location: kernel/sched/fair.c:1106
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810d6890-ffffffff810d68fc: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int task_nr_scan_windows(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e21a0)
Location: kernel/sched/fair.c:1106
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_min
```
**Symbols:**

```
ffffffff810e21a0-ffffffff810e220c: task_nr_scan_windows (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
