# Function: <code>ptrace_event</code>

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
In kernel/fork.c (ffffffff81080409)
Location: include/linux/ptrace.h:143
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108395c)
Location: include/linux/ptrace.h:143
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8113bf63)
Location: include/linux/ptrace.h:143
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_phase2
```
```
In fs/exec.c (ffffffff8121438a)
Location: include/linux/ptrace.h:143
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
In kernel/fork.c (ffffffff81082243)
Location: include/linux/ptrace.h:143
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81086a6e)
Location: include/linux/ptrace.h:143
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81143d2e)
Location: include/linux/ptrace.h:143
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8123b11c)
Location: include/linux/ptrace.h:143
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
In kernel/fork.c (ffffffff81086ca3)
Location: include/linux/ptrace.h:145
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108b9de)
Location: include/linux/ptrace.h:145
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8114dbfe)
Location: include/linux/ptrace.h:145
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8124def8)
Location: include/linux/ptrace.h:145
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
In kernel/fork.c (ffffffff810839fa)
Location: include/linux/ptrace.h:147
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81088b5f)
Location: include/linux/ptrace.h:147
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8115015c)
Location: include/linux/ptrace.h:147
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff81259f4a)
Location: include/linux/ptrace.h:147
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
In kernel/fork.c (ffffffff8108a2e0)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108f8a5)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8115cf1c)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8127c1f5)
Location: include/linux/ptrace.h:148
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
In kernel/fork.c (ffffffff8108daf4)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81093415)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8116b621)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812a2fab)
Location: include/linux/ptrace.h:148
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
In kernel/fork.c (ffffffff81095d84)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109b6d5)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81178ca9)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812b7ff3)
Location: include/linux/ptrace.h:148
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
In kernel/fork.c (ffffffff8109a02c)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fd44)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81185bda)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812d44e6)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff810a060c)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a6347)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81191b54)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812e6076)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff810a7499)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810ae119)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811a6a5b)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8131ccad)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff810a317e)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810a979f)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811a40d8)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff81327e3e)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff810a3d61)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810aa7df)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811a49f6)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8132dd6e)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff810b557e)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810bc30b)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff811ce1ee)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8137b54b)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff810cb8f4)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810d2e08)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8120249d)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff813fa60c)
Location: include/linux/ptrace.h:148
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
In kernel/fork.c (ffffffff810e8f07)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810f195a)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8124a08a)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff8148413c)
Location: include/linux/ptrace.h:148
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
In kernel/fork.c (ffffffff810f4b24)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810fd8c6)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8126137a)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff814b8a4f)
Location: include/linux/ptrace.h:148
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
In kernel/fork.c (ffffffff810fdec4)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff81106736)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8127b57a)
Location: include/linux/ptrace.h:148
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff814eaf5f)
Location: include/linux/ptrace.h:148
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
In kernel/fork.c (ffff8000100f4ed4)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffff8000100fd2f0)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffff80001020955c)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffff80001038e1e8)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (c035364c)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c035a3c8)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (c0448338)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (c0575d2c)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (c00000000013afe0)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c00000000014410c)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (c000000000286628)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (c00000000048676c)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffe0000c1562)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffe0000c5b76)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffe00016b5fc)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffe00025ee24)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff81099f2c)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fc67)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8118a174)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812de656)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff8108896c)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108e697)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff8117d2a4)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812cf986)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff81099edc)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fc17)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81187f44)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812dc466)
Location: include/linux/ptrace.h:155
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
In kernel/fork.c (ffffffff810a1b4f)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a7b87)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/seccomp.c (ffffffff81195898)
Location: include/linux/ptrace.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/exec.c (ffffffff812ed1fd)
Location: include/linux/ptrace.h:155
Inline: True
```
</details>
</li>
</ul>

## Differences
