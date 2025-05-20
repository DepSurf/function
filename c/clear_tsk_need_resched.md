# Function: <code>clear_tsk_need_resched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107e859)
Location: include/linux/sched.h:2884
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff8181faec)
Location: include/linux/sched.h:2884
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810804c7)
Location: include/linux/sched.h:3161
Inline: True
```
```
In kernel/sched/core.c (ffffffff8189a221)
Location: include/linux/sched.h:3161
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81084e2c)
Location: include/linux/sched.h:3317
Inline: True
```
```
In kernel/sched/core.c (ffffffff818ce84a)
Location: include/linux/sched.h:3317
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81081cce)
Location: include/linux/sched.h:1512
Inline: True
```
```
In kernel/sched/core.c (ffffffff81905c71)
Location: include/linux/sched.h:1512
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088596)
Location: include/linux/sched.h:1546
Inline: True
```
```
In kernel/sched/core.c (ffffffff8198fced)
Location: include/linux/sched.h:1546
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108c2f9)
Location: include/linux/sched.h:1668
Inline: True
```
```
In kernel/sched/core.c (ffffffff819ec539)
Location: include/linux/sched.h:1668
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81093d12)
Location: include/linux/sched.h:1681
Inline: True
```
```
In kernel/sched/core.c (ffffffff81a277bb)
Location: include/linux/sched.h:1681
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81098441)
Location: include/linux/sched.h:1754
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81a98057)
Location: include/linux/sched.h:1754
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109ea1b)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81acf92d)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5acd)
Location: include/linux/sched.h:1797
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81bc83a6)
Location: include/linux/sched.h:1797
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a13b9)
Location: include/linux/sched.h:1858
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81c410fc)
Location: include/linux/sched.h:1858
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a2128)
Location: include/linux/sched.h:1880
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81c3307b)
Location: include/linux/sched.h:1880
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b2f18)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81d51a73)
Location: include/linux/sched.h:1997
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c91e7)
Location: include/linux/sched.h:2019
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff81f21f95)
Location: include/linux/sched.h:2019
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e66d7)
Location: include/linux/sched.h:2046
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff820cc7e5)
Location: include/linux/sched.h:2046
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f2047)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff82150a95)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fbc8a)
Location: include/linux/sched.h:1956
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffffffff822338c4)
Location: include/linux/sched.h:1956
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f3108)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/sched/core.c (ffff800010da155c)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0351dc0)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (c0e995a0)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001393e4)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (c000000000ee25d8)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bfdea)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffe0008c4dfa)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109833b)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81a6e79d)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086d81)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81a2ab97)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810982eb)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81adabad)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109fee2)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/core.c (ffffffff81ae705f)
Location: include/linux/sched.h:1747
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
```
</details>
</li>
</ul>

## Differences
