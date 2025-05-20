# Function: <code>task_blk_io_accounting_add</code>

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
In kernel/exit.c (ffffffff810825f4)
Location: include/linux/task_io_accounting_ops.h:48
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/base.c (ffffffff8127b320)
Location: include/linux/task_io_accounting_ops.h:48
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
In kernel/exit.c (ffffffff8108628c)
Location: include/linux/task_io_accounting_ops.h:48
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812a7e20)
Location: include/linux/task_io_accounting_ops.h:48
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
In kernel/exit.c (ffffffff8108b1fc)
Location: include/linux/task_io_accounting_ops.h:48
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812bd700)
Location: include/linux/task_io_accounting_ops.h:48
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
In kernel/exit.c (ffffffff81087f81)
Location: include/linux/task_io_accounting_ops.h:48
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812ca68c)
Location: include/linux/task_io_accounting_ops.h:48
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
In kernel/exit.c (ffffffff8108ed0c)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff812eef1c)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff81092807)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/base.c (ffffffff8131bfe5)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff8109aaeb)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/base.c (ffffffff81333195)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff8109ed60)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8135b0ed)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810a52f0)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff813732fd)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810ad046)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff813bb59d)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810a870f)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff813cd12d)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810a95c6)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff813d3ffd)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810bb0b6)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff8142570d)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810d1a82)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff8149ea80)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810f04d2)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff815337a0)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810fc492)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff8156b990)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff81105b9b)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/base.c (ffffffff815a3145)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffff8000100fb23c)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffff80001043d884)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
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
In kernel/exit.c (c035919c)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (c0603944)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (c00000000014267c)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (c000000000551d34)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffe0000c4e82)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffe0002d6a30)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff8109ec10)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8136b8dd)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff8108d653)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8135c36d)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff8109ebc0)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff813693ad)
Location: include/linux/task_io_accounting_ops.h:49
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
In kernel/exit.c (ffffffff810a6ade)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/base.c (ffffffff8137cc1d)
Location: include/linux/task_io_accounting_ops.h:49
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:do_io_accounting
```
</details>
</li>
</ul>

## Differences
