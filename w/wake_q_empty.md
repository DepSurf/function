# Function: <code>wake_q_empty</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (ffffffff8110f048)
Location: include/linux/sched/wake_q.h:54
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff8110c18e)
Location: include/linux/sched/wake_q.h:54
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff8110dfc6)
Location: include/linux/sched/wake_q.h:54
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff8112d738)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d55d26)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rwsem.c (ffffffff81f25745)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f27c34)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rwsem.c (ffffffff820d1136)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d3774)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rwsem.c (ffffffff821554c8)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff821579f4)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rwsem.c (ffffffff82238308)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In kernel/locking/rtmutex_api.c (ffffffff8223a864)
Location: include/linux/sched/wake_q.h:57
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_unlock
  - kernel/locking/rtmutex_api.c:rt_mutex_unlock
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (c03b5f90)
Location: include/linux/sched/wake_q.h:54
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
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
In kernel/locking/rwsem.c (0)
Location: include/linux/sched/wake_q.h:54
Inline: True
```
</details>
</li>
</ul>

## Differences
