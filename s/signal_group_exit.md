# Function: <code>signal_group_exit</code>

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
In kernel/exit.c (ffffffff81084406)
Location: include/linux/sched.h:805
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff8108ee1c)
Location: include/linux/sched.h:805
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff81213324)
Location: include/linux/sched.h:805
Inline: True
```
```
In fs/coredump.c (ffffffff8126f187)
Location: include/linux/sched.h:805
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810875ae)
Location: include/linux/sched.h:830
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff8109392d)
Location: include/linux/sched.h:830
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff81239e71)
Location: include/linux/sched.h:830
Inline: True
```
```
In fs/coredump.c (ffffffff8129a9c6)
Location: include/linux/sched.h:830
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff8108c50e)
Location: include/linux/sched.h:868
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810988ce)
Location: include/linux/sched.h:868
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff8124cba1)
Location: include/linux/sched.h:868
Inline: True
```
```
In fs/coredump.c (ffffffff812af556)
Location: include/linux/sched.h:868
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff8108967e)
Location: include/linux/sched/signal.h:254
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff81095b69)
Location: include/linux/sched/signal.h:254
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff81258bfd)
Location: include/linux/sched/signal.h:254
Inline: True
```
```
In fs/coredump.c (ffffffff812bc988)
Location: include/linux/sched/signal.h:254
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810903fe)
Location: include/linux/sched/signal.h:255
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff8109c9b9)
Location: include/linux/sched/signal.h:255
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff8127ad96)
Location: include/linux/sched/signal.h:255
Inline: True
```
```
In fs/coredump.c (ffffffff812e0275)
Location: include/linux/sched/signal.h:255
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff81093ebe)
Location: include/linux/sched/signal.h:255
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810a0db9)
Location: include/linux/sched/signal.h:255
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812a2163)
Location: include/linux/sched/signal.h:255
Inline: True
```
```
In fs/coredump.c (ffffffff8130c491)
Location: include/linux/sched/signal.h:255
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff8109c23e)
Location: include/linux/sched/signal.h:264
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810a91f9)
Location: include/linux/sched/signal.h:264
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812b70e7)
Location: include/linux/sched/signal.h:264
Inline: True
```
```
In fs/coredump.c (ffffffff81321cf1)
Location: include/linux/sched/signal.h:264
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810a085b)
Location: include/linux/sched/signal.h:265
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810ad5bd)
Location: include/linux/sched/signal.h:265
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812d496e)
Location: include/linux/sched/signal.h:265
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff81349b31)
Location: include/linux/sched/signal.h:265
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810a6e3b)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810b3bdd)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812e64ee)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff81361dd1)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810ae587)
Location: include/linux/sched/signal.h:266
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810bc69a)
Location: include/linux/sched/signal.h:266
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff8131de60)
Location: include/linux/sched/signal.h:266
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff813a7bd5)
Location: include/linux/sched/signal.h:266
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
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
In kernel/exit.c (ffffffff810a9bd7)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810b798a)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff81329370)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff813b8a7b)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
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
In kernel/exit.c (ffffffff810aac07)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810b8eea)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff8132f180)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff813bfb7b)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
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
In kernel/exit.c (ffffffff810bc727)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810cb47a)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff8137c960)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff8140f9ab)
Location: include/linux/sched/signal.h:267
Inline: True
Inline callers:
  - fs/coredump.c:zap_threads
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/exit.c (ffff8000100fdd28)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffff80001010fbe8)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffff80001038e6b0)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffff8000104284dc)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (c035af88)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (c0367974)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (c0574ce4)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (c05f1118)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (c000000000144e34)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (c000000000157208)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (c000000000485590)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (c0000000005386c8)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffe0000c649e)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffe0000cff64)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffe00025e1f2)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffe0002c66e0)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810a075b)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810adf4d)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812deace)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff8135a3b1)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff8108f177)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff8109c8ad)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812cec0e)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff8134b061)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810a070b)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810ad4ad)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812dc8de)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff81357e81)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/exit.c (ffffffff810a8697)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/exit.c:do_group_exit
  - kernel/exit.c:do_group_exit
```
```
In kernel/signal.c (ffffffff810b567a)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In fs/exec.c (ffffffff812ed69e)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In fs/coredump.c (ffffffff8136b561)
Location: include/linux/sched/signal.h:257
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
</details>
</li>
</ul>

## Differences
