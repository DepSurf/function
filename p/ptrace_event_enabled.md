# Function: <code>ptrace_event_enabled</code>

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
In kernel/fork.c (0)
Location: include/linux/ptrace.h:128
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/ptrace.h:128
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/ptrace.h:128
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/ptrace.h:128
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
In kernel/fork.c (ffffffff810822d5)
Location: include/linux/ptrace.h:128
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (0)
Location: include/linux/ptrace.h:128
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/ptrace.h:128
Inline: True
```
```
In fs/exec.c (ffffffff8123b125)
Location: include/linux/ptrace.h:128
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
In kernel/fork.c (ffffffff81086d35)
Location: include/linux/ptrace.h:130
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (0)
Location: include/linux/ptrace.h:130
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/ptrace.h:130
Inline: True
```
```
In fs/exec.c (ffffffff8124df01)
Location: include/linux/ptrace.h:130
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
In kernel/fork.c (ffffffff81083a8c)
Location: include/linux/ptrace.h:132
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (0)
Location: include/linux/ptrace.h:132
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/ptrace.h:132
Inline: True
```
```
In fs/exec.c (ffffffff81259f53)
Location: include/linux/ptrace.h:132
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
In kernel/fork.c (ffffffff8108a372)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (0)
Location: include/linux/ptrace.h:133
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/linux/ptrace.h:133
Inline: True
```
```
In fs/exec.c (ffffffff8127c1fe)
Location: include/linux/ptrace.h:133
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
In kernel/fork.c (ffffffff8108d873)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81093415)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8116b616)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812a2fb4)
Location: include/linux/ptrace.h:133
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
In kernel/fork.c (ffffffff81095b03)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109b6d5)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81178c9e)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812b7ffc)
Location: include/linux/ptrace.h:133
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
In kernel/fork.c (ffffffff81099e3b)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fd44)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81185bd0)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812d44ef)
Location: include/linux/ptrace.h:140
Inline: True
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
In kernel/fork.c (ffffffff810a041b)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a6347)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81191b49)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812e607f)
Location: include/linux/ptrace.h:140
Inline: True
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
In kernel/fork.c (ffffffff810a72e4)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810ae122)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811a6a51)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8131ccb6)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffffffff810a2fdf)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810a97a8)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811a40ce)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff81327e47)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffffffff810a3b5f)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810aa7e8)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811a49ec)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8132dd77)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffffffff810b537f)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810bc314)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811ce1e4)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8137b554)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffffffff810cb6bf)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810d2e11)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81202491)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff813fa615)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffffffff810e8c7f)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810f1963)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8124a074)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff81484145)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffffffff810f488c)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810fd8cf)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81261364)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff814b8a58)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffffffff810fdc2c)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff8110673f)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8127b564)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff814eaf68)
Location: include/linux/ptrace.h:133
Inline: True
Inline callers:
  - fs/exec.c:exec_binprm
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
In kernel/fork.c (ffff8000100f4c84)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffff8000100fd2f4)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffff800010209554)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffff80001038e1ec)
Location: include/linux/ptrace.h:140
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
In kernel/fork.c (c0353424)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c035a3d4)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (c044832c)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (c0575d2c)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
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
In kernel/fork.c (c00000000013acd0)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c00000000014410c)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (c00000000028661c)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (c000000000486770)
Location: include/linux/ptrace.h:140
Inline: True
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
In kernel/fork.c (ffffffe0000c13da)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffe0000c5b76)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffe00016b5f0)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffe00025ee24)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
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
In kernel/fork.c (ffffffff81099d3b)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fc67)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8118a169)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812de65f)
Location: include/linux/ptrace.h:140
Inline: True
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
In kernel/fork.c (ffffffff8108877b)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108e697)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8117d299)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812cf98f)
Location: include/linux/ptrace.h:140
Inline: True
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
In kernel/fork.c (ffffffff81099ceb)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fc17)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81187f39)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812dc46f)
Location: include/linux/ptrace.h:140
Inline: True
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
In kernel/fork.c (ffffffff810a193b)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a7b87)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8119588d)
Location: include/linux/ptrace.h:140
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812ed206)
Location: include/linux/ptrace.h:140
Inline: True
```
</details>
</li>
</ul>

## Differences
