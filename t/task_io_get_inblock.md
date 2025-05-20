# Function: <code>task_io_get_inblock</code>

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
In kernel/exit.c (0)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
```
```
In kernel/sys.c (0)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
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
In kernel/exit.c (ffffffff810861bc)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810958ef)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
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
In kernel/exit.c (ffffffff8108b12c)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff8109a8df)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
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
In kernel/exit.c (ffffffff81087ec4)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff8109b079)
Location: include/linux/task_io_accounting_ops.h:19
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff8108ec4f)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810a1d59)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff8109274a)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/sys.c (ffffffff810a807b)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff8109aa2e)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/sys.c (ffffffff810b0d8b)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff8109eca0)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810b68da)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810a5230)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810bce9a)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810acf7c)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff810c45da)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810a8645)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff810bf9da)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810a9507)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff810c140a)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810baff7)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff810d3efa)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810d19c9)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff810ecbc4)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810f0419)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff8110df64)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810fc3d9)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff8111a1ed)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff81105ae2)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In kernel/sys.c (ffffffff81123d97)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffff8000100fb198)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffff800010119a00)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (c0359068)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (c036df40)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (c0000000001425cc)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (c000000000161230)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffe0000c4e0a)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffe0000d46da)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff8109eb50)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810b720a)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff8108d58c)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810a5b4a)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff8109eb00)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810b676a)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
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
In kernel/exit.c (ffffffff810a6a17)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In kernel/sys.c (ffffffff810beaea)
Location: include/linux/task_io_accounting_ops.h:20
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:getrusage
```
</details>
</li>
</ul>

## Differences
