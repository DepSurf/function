# Function: <code>__sched_group_set_shares</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff811072f6)
Location: kernel/sched/fair.c:11602
Inline: True
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_shares
```
**Symbols:**

```
ffffffff811072a0-ffffffff81107431: __sched_group_set_shares (STB_LOCAL)
ffffffff81ca6442-ffffffff81ca645d: __sched_group_set_shares.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11720
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_shares
```
**Symbols:**

```
ffffffff811244d0-ffffffff8112465a: __sched_group_set_shares (STB_LOCAL)
ffffffff81e55d1a-ffffffff81e55d37: __sched_group_set_shares.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12236
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_shares
```
**Symbols:**

```
ffffffff8114c4b0-ffffffff8114c642: __sched_group_set_shares (STB_LOCAL)
ffffffff82056f90-ffffffff82056fad: __sched_group_set_shares.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12554
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_shares
```
**Symbols:**

```
ffffffff8115a740-ffffffff8115a8d5: __sched_group_set_shares (STB_LOCAL)
ffffffff820d56af-ffffffff820d56ca: __sched_group_set_shares.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __sched_group_set_shares(struct task_group *tg, long unsigned int shares);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12977
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:sched_group_set_shares
```
**Symbols:**

```
ffffffff8116c5d0-ffffffff8116c76b: __sched_group_set_shares (STB_LOCAL)
ffffffff821b070d-ffffffff821b0728: __sched_group_set_shares.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
