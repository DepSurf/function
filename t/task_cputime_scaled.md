# Function: <code>task_cputime_scaled</code>

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
In kernel/delayacct.c (0)
Location: include/linux/sched.h:2050
Inline: True
```
```
In kernel/tsacct.c (ffffffff8113f1c8)
Location: include/linux/sched.h:2050
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (0)
Location: include/linux/sched.h:2192
Inline: True
```
```
In kernel/tsacct.c (ffffffff811477ce)
Location: include/linux/sched.h:2192
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (0)
Location: include/linux/sched.h:2290
Inline: True
```
```
In kernel/tsacct.c (ffffffff8115166e)
Location: include/linux/sched.h:2290
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (0)
Location: include/linux/sched/cputime.h:46
Inline: True
```
```
In kernel/tsacct.c (ffffffff81153d13)
Location: include/linux/sched/cputime.h:46
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (0)
Location: include/linux/sched/cputime.h:47
Inline: True
```
```
In kernel/tsacct.c (ffffffff81160513)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8116e1fe)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff8116f439)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8117bc3e)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff8117cf39)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff81188a5e)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff81189dfa)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8119499e)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff81195d0a)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff811a99fe)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff811aaee5)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff811a701e)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff811a849a)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff811a7b5e)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff811a9016)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff811d167b)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff811d2b6b)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff81205c2b)
Location: include/linux/sched/cputime.h:48
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff8120750a)
Location: include/linux/sched/cputime.h:48
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8124ddfb)
Location: include/linux/sched/cputime.h:48
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff8124f89a)
Location: include/linux/sched/cputime.h:48
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8126515b)
Location: include/linux/sched/cputime.h:39
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff81266c4a)
Location: include/linux/sched/cputime.h:39
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8127efbf)
Location: include/linux/sched/cputime.h:39
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff81280b78)
Location: include/linux/sched/cputime.h:39
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffff80001020ca94)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffff80001020dfc4)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (c044b434)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (c044ca94)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (c00000000028a740)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (c00000000028c1c8)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffe00016dd9c)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffe00016ee4a)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8118cfbe)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff8118e32a)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff811800bf)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff81181454)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff8118ad8e)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff8118c0fa)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
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
In kernel/delayacct.c (ffffffff811986fe)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_add_tsk
```
```
In kernel/tsacct.c (ffffffff81199a84)
Location: include/linux/sched/cputime.h:47
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
</details>
</li>
</ul>

## Differences
