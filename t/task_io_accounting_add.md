# Function: <code>task_io_accounting_add</code>

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
In kernel/exit.c (ffffffff810825b8)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/base.c (ffffffff8127b319)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8108622c)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812a7e19)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8108b19c)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812bd6f9)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff81087f2d)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812ca685)
Location: include/linux/task_io_accounting_ops.h:107
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8108ecb8)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812eef15)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810927b3)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/base.c (ffffffff8131bfe5)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8109aa97)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/base.c (ffffffff81333195)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8109ed08)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8135b0c6)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810a5298)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff813732d6)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810acfe7)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff813bb576)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810a86b0)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff813cd106)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810a956e)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff813d3fd6)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810bb05e)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff814256e6)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810d1a2e)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff8149ea80)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810f047e)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff815337a0)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810fc43e)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff8156b990)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff81105b47)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff815a3122)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffff8000100fb1f8)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffff80001043d83c)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (c03590ec)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (c06038c8)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (c000000000142630)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (c000000000551d00)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffe0000c4e60)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffe0002d6a1c)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8109ebb8)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8136b8b6)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8108d5f4)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8135c346)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff8109eb68)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff81369386)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
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
In kernel/exit.c (ffffffff810a6a7f)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8137cbf6)
Location: include/linux/task_io_accounting_ops.h:108
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
```
</details>
</li>
</ul>

## Differences
