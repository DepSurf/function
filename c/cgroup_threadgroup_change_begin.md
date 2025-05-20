# Function: <code>cgroup_threadgroup_change_begin</code>

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
In kernel/fork.c (ffffffff8107eb6b)
Location: include/linux/cgroup-defs.h:507
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81090867)
Location: include/linux/cgroup-defs.h:507
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff8121342e)
Location: include/linux/cgroup-defs.h:507
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
In kernel/fork.c (ffffffff810812ed)
Location: include/linux/cgroup-defs.h:530
Inline: True
```
```
In kernel/signal.c (ffffffff81093907)
Location: include/linux/cgroup-defs.h:530
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff81239f81)
Location: include/linux/cgroup-defs.h:530
Inline: True
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
In kernel/fork.c (ffffffff81085cd7)
Location: include/linux/cgroup-defs.h:534
Inline: True
```
```
In kernel/signal.c (ffffffff81098897)
Location: include/linux/cgroup-defs.h:534
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff8124ccbc)
Location: include/linux/cgroup-defs.h:534
Inline: True
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
In kernel/fork.c (ffffffff810826ec)
Location: include/linux/cgroup-defs.h:554
Inline: True
```
```
In kernel/signal.c (ffffffff81095b32)
Location: include/linux/cgroup-defs.h:554
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff81258cf3)
Location: include/linux/cgroup-defs.h:554
Inline: True
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
In kernel/fork.c (ffffffff810894e9)
Location: include/linux/cgroup-defs.h:674
Inline: True
```
```
In kernel/signal.c (ffffffff8109c982)
Location: include/linux/cgroup-defs.h:674
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff8127ae82)
Location: include/linux/cgroup-defs.h:674
Inline: True
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
In kernel/fork.c (ffffffff8108cf00)
Location: include/linux/cgroup-defs.h:686
Inline: True
```
```
In kernel/signal.c (ffffffff810a0d82)
Location: include/linux/cgroup-defs.h:686
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812a2566)
Location: include/linux/cgroup-defs.h:686
Inline: True
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
In kernel/fork.c (ffffffff81094a26)
Location: include/linux/cgroup-defs.h:695
Inline: True
```
```
In kernel/signal.c (ffffffff810a91c2)
Location: include/linux/cgroup-defs.h:695
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812b7145)
Location: include/linux/cgroup-defs.h:695
Inline: True
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
In kernel/fork.c (ffffffff810991d9)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ad583)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812d4b41)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffffffff8109f7d1)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b3ba3)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812e66c1)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810bc655)
Location: include/linux/cgroup-defs.h:731
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81177dc3)
Location: include/linux/cgroup-defs.h:731
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff8131df77)
Location: include/linux/cgroup-defs.h:731
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810b7945)
Location: include/linux/cgroup-defs.h:716
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81174ae3)
Location: include/linux/cgroup-defs.h:716
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff81329487)
Location: include/linux/cgroup-defs.h:716
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810b8ea5)
Location: include/linux/cgroup-defs.h:716
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff811756a3)
Location: include/linux/cgroup-defs.h:716
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff8132f297)
Location: include/linux/cgroup-defs.h:716
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810cb435)
Location: include/linux/cgroup-defs.h:720
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff8119cc33)
Location: include/linux/cgroup-defs.h:720
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff8137ca77)
Location: include/linux/cgroup-defs.h:720
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810e4a85)
Location: include/linux/cgroup-defs.h:721
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccf23)
Location: include/linux/cgroup-defs.h:721
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff813fbda9)
Location: include/linux/cgroup-defs.h:721
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff811050d5)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff812104e3)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff81484e59)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff81111355)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81225ef3)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff814b9dd9)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff8111ace5)
Location: include/linux/cgroup-defs.h:785
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff8123db83)
Location: include/linux/cgroup-defs.h:785
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff814ec355)
Location: include/linux/cgroup-defs.h:785
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffff8000100f3e70)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff80001010fbac)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffff80001038e9c0)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (c0352848)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c036792c)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (c0574f28)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (c00000000013a1c4)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c0000000001571c0)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (c0000000004858f8)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffffffe0000c0668)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000cff1e)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffe00025e49e)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffffffff810990f1)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810adf13)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812deca1)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffffffff81087b41)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8109c873)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812cedc6)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffffffff810990a1)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ad473)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812dcab1)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffffffff810a0ccb)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b5631)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812ed84c)
Location: include/linux/cgroup-defs.h:738
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
</details>
</li>
</ul>

## Differences
