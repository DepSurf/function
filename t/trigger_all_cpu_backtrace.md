# Function: <code>trigger_all_cpu_backtrace</code>

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
In kernel/hung_task.c (ffffffff8113a6a1)
Location: include/linux/nmi.h:39
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff814ed896)
Location: include/linux/nmi.h:39
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff81142bd0)
Location: include/linux/nmi.h:39
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff8153e506)
Location: include/linux/nmi.h:39
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff8114c9ba)
Location: include/linux/nmi.h:56
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff8156ab56)
Location: include/linux/nmi.h:56
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff8114e93a)
Location: include/linux/nmi.h:103
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff8157f186)
Location: include/linux/nmi.h:103
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff8115b1ca)
Location: include/linux/nmi.h:136
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff815e3cf6)
Location: include/linux/nmi.h:136
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff81169d28)
Location: include/linux/nmi.h:136
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff8161cfa5)
Location: include/linux/nmi.h:136
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff81176c0c)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff8163a205)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff81183ac0)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff8166e535)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff8118f930)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff81690b75)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810a837e)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
```
```
In kernel/hung_task.c (ffffffff811a448b)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff81743365)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810a40ce)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
```
```
In kernel/hung_task.c (ffffffff811a15e5)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff8175f1e5)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810a4d1e)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
```
```
In kernel/hung_task.c (ffffffff811a223d)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff81743055)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810b655e)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
```
```
In kernel/hung_task.c (ffffffff811cba17)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff817c3a85)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810ccafa)
Location: include/linux/nmi.h:146
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
```
```
In kernel/hung_task.c (ffffffff811ff7df)
Location: include/linux/nmi.h:146
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff819006c5)
Location: include/linux/nmi.h:146
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810ea9ba)
Location: include/linux/nmi.h:146
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff812471e8)
Location: include/linux/nmi.h:146
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff81a5a2b5)
Location: include/linux/nmi.h:146
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810f659a)
Location: include/linux/nmi.h:158
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff8125e27b)
Location: include/linux/nmi.h:158
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff81aa48e5)
Location: include/linux/nmi.h:158
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/panic.c (ffffffff810ff94a)
Location: include/linux/nmi.h:158
Inline: True
Inline callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff812781bb)
Location: include/linux/nmi.h:158
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
```
```
In drivers/tty/sysrq.c (ffffffff81af72e5)
Location: include/linux/nmi.h:158
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (0)
Location: include/linux/nmi.h:175
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/nmi.h:175
Inline: True
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
In kernel/hung_task.c (c0445d30)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (c09696d4)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (c0000000002834fc)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (c000000000902a2c)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (0)
Location: include/linux/nmi.h:175
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/nmi.h:175
Inline: True
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
In kernel/hung_task.c (ffffffff81187f50)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff816565f5)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff8117b090)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff81636985)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff81185d20)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff816849b5)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
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
In kernel/hung_task.c (ffffffff81193661)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In drivers/tty/sysrq.c (ffffffff8169efc5)
Location: include/linux/nmi.h:144
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
</details>
</li>
</ul>

## Differences
