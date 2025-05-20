# Function: <code>ttwu_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ttwu_stat(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a49c0)
Location: kernel/sched/core.c:1664
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810a49c0-ffffffff810a4a74: ttwu_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ttwu_stat(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a80e0)
Location: kernel/sched/core.c:1630
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810a80e0-ffffffff810a81c8: ttwu_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ttwu_stat(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b04b0)
Location: kernel/sched/core.c:1641
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810b04b0-ffffffff810b05a8: ttwu_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81906293)
Location: kernel/sched/core.c:1603
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810ac9e0-ffffffff810acaca: ttwu_stat.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff819902e0)
Location: kernel/sched/core.c:1622
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810b3950-ffffffff810b3a3a: ttwu_stat.part.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ttwu_stat(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810baba0)
Location: kernel/sched/core.c:1618
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810baba0-ffffffff810bac52: ttwu_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ttwu_stat(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3dc0)
Location: kernel/sched/core.c:1616
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810c3dc0-ffffffff810c3e72: ttwu_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d063b)
Location: kernel/sched/core.c:2056
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da5eb)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ttwu_stat(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddf90)
Location: kernel/sched/core.c:2240
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810ddf90-ffffffff810de036: ttwu_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ttwu_stat(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dada0)
Location: kernel/sched/core.c:2895
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810dada0-ffffffff810dae65: ttwu_stat (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810e2e1f)
Location: kernel/sched/core.c:2916
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
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
In kernel/sched/core.c (ffffffff810f9860)
Location: kernel/sched/core.c:3480
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
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
In kernel/sched/core.c (ffffffff81115dbe)
Location: kernel/sched/core.c:3579
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
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
In kernel/sched/core.c (ffffffff8113d298)
Location: kernel/sched/core.c:3639
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
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
In kernel/sched/core.c (ffffffff81150d1d)
Location: kernel/sched/core.c:3708
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
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
In kernel/sched/core.c (ffffffff8115cb1b)
Location: kernel/sched/core.c:3727
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013a0b8)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0389c28)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001877e0)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e99a4)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4a9b)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c30eb)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d18db)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc29d)
Location: kernel/sched/core.c:2176
Inline: True
Inline callers:
  - kernel/sched/core.c:try_to_wake_up
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
