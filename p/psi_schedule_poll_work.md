# Function: <code>psi_schedule_poll_work</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6530)
Location: kernel/sched/psi.c:555
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff810f6530-ffffffff810f6578: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff811022d0)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff811022d0-ffffffff81102318: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110ca20)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff8110ca20-ffffffff8110ca68: psi_schedule_poll_work (STB_LOCAL)
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
In kernel/sched/psi.c (ffffffff8110a37f)
Location: kernel/sched/psi.c:550
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_poll_work
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
In kernel/sched/psi.c (ffffffff8110bf1c)
Location: kernel/sched/psi.c:559
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
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
In kernel/sched/psi.c (ffffffff8112ac47)
Location: kernel/sched/psi.c:570
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_poll_worker
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
In kernel/sched/build_utility.c (ffffffff8113f811)
Location: kernel/sched/psi.c:569
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_poll_worker
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
In kernel/sched/build_utility.c (ffffffff8116a3ea)
Location: kernel/sched/psi.c:594
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_poll_worker
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010166f98)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffff800010166f98-ffff800010167014: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b2f3c)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
c03b2f3c-c03b2fac: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bea00)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
c0000000001bea00-c0000000001bea8c: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109150)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffe000109150-ffffffe0001091aa: psi_schedule_poll_work (STB_LOCAL)
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
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fb5e0)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff810fb5e0-ffffffff810fb628: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810eb800)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff810eb800-ffffffff810eb848: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f87a0)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff810f87a0-ffffffff810f87e8: psi_schedule_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void psi_schedule_poll_work(struct psi_group *group, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff811038e0)
Location: kernel/sched/psi.c:556
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_poll_work
```
**Symbols:**

```
ffffffff811038e0-ffffffff8110393c: psi_schedule_poll_work (STB_LOCAL)
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
