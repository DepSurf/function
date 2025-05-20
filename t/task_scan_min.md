# Function: <code>task_scan_min</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b1db0)
Location: kernel/sched/fair.c:841
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_tick_numa
```
**Symbols:**

```
ffffffff810b1db0-ffffffff810b1e41: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4970)
Location: kernel/sched/fair.c:975
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_numa
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
```
**Symbols:**

```
ffffffff810b4970-ffffffff810b49c4: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810baf50)
Location: kernel/sched/fair.c:1099
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_numa
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
```
**Symbols:**

```
ffffffff810baf50-ffffffff810bafa4: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b5800)
Location: kernel/sched/fair.c:1096
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_numa
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
```
**Symbols:**

```
ffffffff810b5800-ffffffff810b5854: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bcb20)
Location: kernel/sched/fair.c:1099
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810bcb20-ffffffff810bcb74: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4860)
Location: kernel/sched/fair.c:1086
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810c4860-ffffffff810c48b4: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cdac0)
Location: kernel/sched/fair.c:1082
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810cdac0-ffffffff810cdb14: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5dd0)
Location: kernel/sched/fair.c:1129
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810d5dd0-ffffffff810d5e26: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e03d0)
Location: kernel/sched/fair.c:1128
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810e03d0-ffffffff810e0426: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ecb67)
Location: kernel/sched/fair.c:1139
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea967)
Location: kernel/sched/fair.c:1146
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee402)
Location: kernel/sched/fair.c:1143
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff8110545e)
Location: kernel/sched/fair.c:1132
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff8111c45d)
Location: kernel/sched/fair.c:1134
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff81143fa3)
Location: kernel/sched/fair.c:1173
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff81153f3d)
Location: kernel/sched/fair.c:1190
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff8116008d)
Location: kernel/sched/fair.c:1431
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
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
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101401d8)
Location: kernel/sched/fair.c:1128
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffff8000101401d8-ffff80001014023c: task_scan_min (STB_LOCAL)
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
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000018f3c0)
Location: kernel/sched/fair.c:1128
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
c00000000018f3c0-c00000000018f440: task_scan_min (STB_LOCAL)
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
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810da580)
Location: kernel/sched/fair.c:1128
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810da580-ffffffff810da5d6: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9590)
Location: kernel/sched/fair.c:1128
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810c9590-ffffffff810c95e6: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6900)
Location: kernel/sched/fair.c:1128
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810d6900-ffffffff810d6956: task_scan_min (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int task_scan_min(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2210)
Location: kernel/sched/fair.c:1128
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
```
**Symbols:**

```
ffffffff810e2210-ffffffff810e2266: task_scan_min (STB_LOCAL)
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
