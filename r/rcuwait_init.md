# Function: <code>rcuwait_init</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d45f3)
Location: include/linux/rcuwait.h:26
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff810dc553)
Location: include/linux/rcuwait.h:27
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff810e4ba3)
Location: include/linux/rcuwait.h:27
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff810f0183)
Location: include/linux/rcuwait.h:27
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff810f87e6)
Location: include/linux/rcuwait.h:27
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff81104626)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff8110f12d)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/sched/core.c (ffffffff82fdb132)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110c2ed)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/sched/core.c (ffffffff831e5c30)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8110e12d)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/sched/core.c (ffffffff832c9c84)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8112d87d)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/sched/core.c (ffffffff8347cedc)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8114e88d)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/sched/core.c (ffffffff83ea82ec)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8117d92d)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/sched/core.c (ffffffff836ccbbc)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8118e5cd)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/sched/core.c (ffffffff838fdf9d)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
```
```
In kernel/locking/percpu-rwsem.c (ffffffff8119cf7d)
Location: include/linux/rcuwait.h:23
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffff80001016a280)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (c03b627c)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (c0000000001c1e60)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffe00010b0ea)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff810fd936)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff810edb36)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff810faaf6)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
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
In kernel/locking/percpu-rwsem.c (ffffffff81105cc6)
Location: include/linux/rcuwait.h:22
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:__percpu_init_rwsem
```
</details>
</li>
</ul>

## Differences
