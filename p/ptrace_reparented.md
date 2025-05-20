# Function: <code>ptrace_reparented</code>

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
In kernel/exit.c (ffffffff81082c06)
Location: include/linux/ptrace.h:85
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8108eb90)
Location: include/linux/ptrace.h:85
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:get_signal
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
In kernel/exit.c (ffffffff81085c75)
Location: include/linux/ptrace.h:85
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff81093733)
Location: include/linux/ptrace.h:85
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8108abe5)
Location: include/linux/ptrace.h:87
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810986c3)
Location: include/linux/ptrace.h:87
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff81087b8e)
Location: include/linux/ptrace.h:89
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff81095984)
Location: include/linux/ptrace.h:89
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8108e91e)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109c7df)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8109247b)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a0c4c)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8109a789)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a8f4f)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8109f2d2)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aee67)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff810a5862)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b547e)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff810ad403)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
```
```
In kernel/signal.c (ffffffff810be1c0)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff810a8ad3)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
```
```
In kernel/signal.c (ffffffff810b94b0)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff810a9a65)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
```
```
In kernel/signal.c (ffffffff810baab5)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff810bb573)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
```
```
In kernel/signal.c (ffffffff810cd46e)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff810d1f56)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810e5367)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
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
In kernel/exit.c (ffffffff810f09b6)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff811059e5)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
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
In kernel/exit.c (ffffffff810fc971)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff81111c77)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
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
In kernel/exit.c (ffffffff81106073)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:exit_notify
```
```
In kernel/signal.c (ffffffff8111b617)
Location: include/linux/ptrace.h:90
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
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
In kernel/exit.c (ffff8000100fb850)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffff8000101113e4)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (c0359814)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c0368e04)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (c000000000142de0)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c000000000158ca8)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffe0000c53ae)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffe0000d0d78)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8109f182)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810af7ee)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8108dbb6)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109e120)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff8109f132)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aed4e)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
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
In kernel/exit.c (ffffffff810a7091)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b703e)
Location: include/linux/ptrace.h:97
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
```
</details>
</li>
</ul>

## Differences
