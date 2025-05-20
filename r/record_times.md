# Function: <code>record_times</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ef410)
Location: kernel/sched/psi.c:400
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff810ef410-ffffffff810ef4c7: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f5c90)
Location: kernel/sched/psi.c:625
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff810f5c90-ffffffff810f5d19: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81101a20)
Location: kernel/sched/psi.c:626
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff81101a20-ffffffff81101aa9: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110c2b0)
Location: kernel/sched/psi.c:626
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_group_change
```
**Symbols:**

```
ffffffff8110c2b0-ffffffff8110c339: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff811094b0)
Location: kernel/sched/psi.c:642
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_group_change
```
**Symbols:**

```
ffffffff811094b0-ffffffff81109539: record_times (STB_LOCAL)
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
In kernel/sched/psi.c (ffffffff8110bde9)
Location: kernel/sched/psi.c:651
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
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
In kernel/sched/psi.c (ffffffff8112aa9f)
Location: kernel/sched/psi.c:662
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
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
In kernel/sched/build_utility.c (ffffffff8113f685)
Location: kernel/sched/psi.c:661
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166c00)
Location: kernel/sched/psi.c:726
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_group_change
```
**Symbols:**

```
ffffffff81166c00-ffffffff81166c5a: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177070)
Location: kernel/sched/psi.c:749
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_group_change
```
**Symbols:**

```
ffffffff81177070-ffffffff811770ca: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184fe0)
Location: kernel/sched/psi.c:738
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_group_change
```
**Symbols:**

```
ffffffff81184fe0-ffffffff8118503a: record_times (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffff800010166bb8)
Location: kernel/sched/psi.c:626
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffff800010166bb8-ffff800010166c90: record_times.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (c03b3268)
Location: kernel/sched/psi.c:626
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
c03b3268-c03b3340: record_times.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (c0000000001be8d0)
Location: kernel/sched/psi.c:626
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
c0000000001be8d0-c0000000001be9f8: record_times.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109086)
Location: kernel/sched/psi.c:626
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffe000109086-ffffffe000109150: record_times.isra.0 (STB_LOCAL)
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
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fad30)
Location: kernel/sched/psi.c:626
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff810fad30-ffffffff810fadb9: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810eaf50)
Location: kernel/sched/psi.c:626
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff810eaf50-ffffffff810eafd9: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f7ef0)
Location: kernel/sched/psi.c:626
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff810f7ef0-ffffffff810f7f79: record_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void record_times(struct psi_group_cpu *groupc, int cpu, bool memstall_tick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103030)
Location: kernel/sched/psi.c:626
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_memstall_tick
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff81103030-ffffffff811030b9: record_times (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
