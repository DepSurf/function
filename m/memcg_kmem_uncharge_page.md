# Function: <code>memcg_kmem_uncharge_page</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a46b6)
Location: include/linux/memcontrol.h:1382
Inline: True
```
```
In fs/pipe.c (ffffffff8131ec4c)
Location: include/linux/memcontrol.h:1382
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810a1489)
Location: include/linux/memcontrol.h:1640
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff8132a16c)
Location: include/linux/memcontrol.h:1640
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810a2204)
Location: include/linux/memcontrol.h:1670
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff8133011c)
Location: include/linux/memcontrol.h:1670
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810b3010)
Location: include/linux/memcontrol.h:1679
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
  - kernel/fork.c:put_task_stack
```
```
In fs/pipe.c (ffffffff8137d8dc)
Location: include/linux/memcontrol.h:1679
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810c8ff0)
Location: include/linux/memcontrol.h:1738
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In fs/pipe.c (ffffffff813fe5ff)
Location: include/linux/memcontrol.h:1738
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810e64b0)
Location: include/linux/memcontrol.h:1772
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In fs/pipe.c (ffffffff8148829f)
Location: include/linux/memcontrol.h:1772
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810f1e20)
Location: include/linux/memcontrol.h:1795
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In fs/pipe.c (ffffffff814bd1a7)
Location: include/linux/memcontrol.h:1795
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
In kernel/fork.c (ffffffff810fba82)
Location: include/linux/memcontrol.h:1851
Inline: True
Inline callers:
  - kernel/fork.c:exit_task_stack_account
```
```
In fs/pipe.c (ffffffff814ef644)
Location: include/linux/memcontrol.h:1851
Inline: True
Inline callers:
  - fs/pipe.c:anon_pipe_buf_try_steal
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
