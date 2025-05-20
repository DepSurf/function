# Function: <code>task_pid_type</code>

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
In kernel/exit.c (ffffffff81082271)
Location: kernel/exit.c:908
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff81085920)
Location: kernel/exit.c:983
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff8108a890)
Location: kernel/exit.c:973
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff81087890)
Location: kernel/exit.c:1006
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff8108e620)
Location: kernel/exit.c:1005
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff810920f0)
Location: kernel/exit.c:1005
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff8109a3f0)
Location: include/linux/sched/signal.h:571
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff8109ef60)
Location: include/linux/sched/signal.h:602
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff810a54f0)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff810ad2f9)
Location: include/linux/sched/signal.h:617
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff810a89c9)
Location: include/linux/sched/signal.h:630
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff810a982a)
Location: include/linux/sched/signal.h:636
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff810bb321)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In kernel/sched/core_sched.c (ffffffff8112c5c9)
Location: include/linux/sched/signal.h:634
Inline: True
Inline callers:
  - kernel/sched/core_sched.c:sched_core_share_pid
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
In kernel/exit.c (ffffffff810d0962)
Location: include/linux/sched/signal.h:674
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
```
```
In kernel/sched/build_utility.c (ffffffff8114b833)
Location: include/linux/sched/signal.h:674
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
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
In kernel/exit.c (ffffffff810ef302)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
```
```
In kernel/sched/build_utility.c (ffffffff8117a2c3)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
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
In kernel/exit.c (ffffffff810fb322)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
```
```
In kernel/sched/build_utility.c (ffffffff8118ad1b)
Location: include/linux/sched/signal.h:675
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
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
In kernel/exit.c (ffffffff81104c52)
Location: include/linux/sched/signal.h:667
Inline: True
Inline callers:
  - kernel/exit.c:child_wait_callback
  - kernel/exit.c:wait_consider_task
```
```
In kernel/sched/build_utility.c (ffffffff8119965a)
Location: include/linux/sched/signal.h:667
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_core_share_pid
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
In kernel/exit.c (ffff8000100fb49c)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (c0359470)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (c0000000001428e4)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffe0000c5094)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff8109ee10)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff8108d850)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff8109edc0)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
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
In kernel/exit.c (ffffffff810a6d00)
Location: include/linux/sched/signal.h:594
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
</details>
</li>
</ul>

## Differences
