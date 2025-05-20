# Function: <code>test_restore_sigmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e601)
Location: arch/x86/include/asm/thread_info.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched.h:2733
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched.h:2833
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched/signal.h:404
Inline: True
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
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched/signal.h:405
Inline: True
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
In arch/x86/kernel/signal.c (ffffffff8102d6b6)
Location: include/linux/sched/signal.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff8102e900)
Location: include/linux/sched/signal.h:445
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81030b9d)
Location: include/linux/sched/signal.h:462
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81031025)
Location: include/linux/sched/signal.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81033969)
Location: include/linux/sched/signal.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
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
In arch/x86/kernel/signal.c (ffffffff810343d9)
Location: include/linux/sched/signal.h:490
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:setup_rt_frame
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
In arch/x86/kernel/signal.c (ffffffff81035ee4)
Location: include/linux/sched/signal.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103b165)
Location: include/linux/sched/signal.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810420eb)
Location: include/linux/sched/signal.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:handle_signal
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
In arch/x86/kernel/signal_64.c (ffffffff8104bbe6)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055d10)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
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
In arch/x86/kernel/signal_64.c (ffffffff8104c466)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/signal_32.c (ffffffff81056d00)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
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
In arch/x86/kernel/signal_64.c (ffffffff810536e6)
Location: include/linux/sched/signal.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105df50)
Location: include/linux/sched/signal.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
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
In arch/arm64/kernel/signal.c (ffff8000100934e8)
Location: include/linux/sched/signal.h:430
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
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
In arch/arm/kernel/signal.c (c030e814)
Location: include/linux/sched/signal.h:430
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
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
In arch/powerpc/kernel/signal.c (c0000000000237c4)
Location: include/linux/sched/signal.h:454
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
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
In arch/riscv/kernel/signal.c (ffffffe0000b65fa)
Location: include/linux/sched/signal.h:430
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
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
In arch/x86/kernel/signal.c (ffffffff81031185)
Location: include/linux/sched/signal.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81020ba5)
Location: include/linux/sched/signal.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81030fe5)
Location: include/linux/sched/signal.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
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
In arch/x86/kernel/signal.c (ffffffff81031e75)
Location: include/linux/sched/signal.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
</details>
</li>
</ul>

## Differences
