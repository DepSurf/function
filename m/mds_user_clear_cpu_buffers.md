# Function: <code>mds_user_clear_cpu_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810047f5)
Location: arch/x86/include/asm/nospec-branch.h:344
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff81035d5b)
Location: arch/x86/include/asm/nospec-branch.h:344
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
In arch/x86/entry/common.c (ffffffff81004855)
Location: arch/x86/include/asm/nospec-branch.h:344
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff81036576)
Location: arch/x86/include/asm/nospec-branch.h:344
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
In arch/x86/entry/common.c (ffffffff81bbc7ec)
Location: arch/x86/include/asm/nospec-branch.h:286
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/entry/common.c:syscall_return_slowpath
  - arch/x86/entry/common.c:prepare_exit_to_usermode
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbdf54)
Location: arch/x86/include/asm/nospec-branch.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
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
In arch/x86/kernel/nmi.c (ffffffff81c367f8)
Location: arch/x86/include/asm/nospec-branch.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In kernel/entry/common.c (ffffffff81c38a29)
Location: arch/x86/include/asm/nospec-branch.h:286
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
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
In arch/x86/kernel/nmi.c (ffffffff81c28c88)
Location: arch/x86/include/asm/nospec-branch.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In kernel/entry/common.c (ffffffff81c2ae29)
Location: arch/x86/include/asm/nospec-branch.h:285
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
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
In arch/x86/kernel/nmi.c (ffffffff81d46e22)
Location: arch/x86/include/asm/nospec-branch.h:289
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In kernel/entry/common.c (ffffffff81d493b9)
Location: arch/x86/include/asm/nospec-branch.h:289
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
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
In arch/x86/kernel/nmi.c (ffffffff81f1536d)
Location: arch/x86/include/asm/nospec-branch.h:380
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In kernel/entry/common.c (ffffffff81f18849)
Location: arch/x86/include/asm/nospec-branch.h:380
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
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
In arch/x86/kernel/nmi.c (ffffffff820bc7ff)
Location: arch/x86/include/asm/nospec-branch.h:556
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In kernel/entry/common.c (ffffffff820bfe89)
Location: arch/x86/include/asm/nospec-branch.h:556
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
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
In arch/x86/kernel/nmi.c (ffffffff8213e083)
Location: arch/x86/include/asm/nospec-branch.h:578
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In kernel/entry/common.c (ffffffff82141cc9)
Location: arch/x86/include/asm/nospec-branch.h:578
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:exit_to_user_mode
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/entry/common.c (ffffffff81004855)
Location: arch/x86/include/asm/nospec-branch.h:344
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff810366d6)
Location: arch/x86/include/asm/nospec-branch.h:344
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
In arch/x86/entry/common.c (ffffffff81002ea8)
Location: arch/x86/include/asm/nospec-branch.h:344
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff8102601e)
Location: arch/x86/include/asm/nospec-branch.h:344
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
In arch/x86/entry/common.c (ffffffff81004815)
Location: arch/x86/include/asm/nospec-branch.h:344
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff81036536)
Location: arch/x86/include/asm/nospec-branch.h:344
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
In arch/x86/entry/common.c (ffffffff81004955)
Location: arch/x86/include/asm/nospec-branch.h:344
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/kernel/nmi.c (ffffffff81037536)
Location: arch/x86/include/asm/nospec-branch.h:344
Inline: True
```
</details>
</li>
</ul>

## Differences
