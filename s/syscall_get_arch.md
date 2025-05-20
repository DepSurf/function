# Function: <code>syscall_get_arch</code>

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
In kernel/auditsc.c (ffffffff811285b8)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_syscall_entry
  - kernel/auditsc.c:__audit_seccomp
```
```
In kernel/seccomp.c (ffffffff8113b51b)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/auditsc.c (ffffffff81131ae4)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff81143a7b)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/auditsc.c (ffffffff8113b851)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff8114d94f)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_send_sigsys
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/auditsc.c (ffffffff8113cf1d)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff8114fa63)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/auditsc.c (ffffffff81149cda)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff8115c013)
Location: arch/x86/include/asm/syscall.h:235
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/auditsc.c (ffffffff811585ca)
Location: arch/x86/include/asm/syscall.h:239
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff8116ac23)
Location: arch/x86/include/asm/syscall.h:239
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_init_siginfo
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/auditsc.c (ffffffff811655e2)
Location: arch/x86/include/asm/syscall.h:239
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff81178e30)
Location: arch/x86/include/asm/syscall.h:239
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (ffffffff810a6b9e)
Location: arch/x86/include/asm/syscall.h:160
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffffffff8117214b)
Location: arch/x86/include/asm/syscall.h:160
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff81185b21)
Location: arch/x86/include/asm/syscall.h:160
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (ffffffff810ad462)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffffffff8117dffb)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff81191a9c)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (ffffffff810b4c70)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffffffff811913eb)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff811a67fe)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/ptrace.c (ffffffff810afe50)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bcde)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/auditsc.c (ffffffff8118e60b)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff811a3e0e)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/ptrace.c (ffffffff810b13e0)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113cfce)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/auditsc.c (ffffffff8118f58b)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff811a47db)
Location: arch/x86/include/asm/syscall.h:155
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/ptrace.c (ffffffff810c36c0)
Location: arch/x86/include/asm/syscall.h:154
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/signal.c (ffffffff810ccb01)
Location: arch/x86/include/asm/syscall.h:154
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811600ee)
Location: arch/x86/include/asm/syscall.h:154
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/auditsc.c (ffffffff811b846b)
Location: arch/x86/include/asm/syscall.h:154
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff811cdac5)
Location: arch/x86/include/asm/syscall.h:154
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/ptrace.c (ffffffff810dae2e)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/signal.c (ffffffff810e3e1f)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a5d6)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/auditsc.c (ffffffff811eb332)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff81201ab5)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/ptrace.c (ffffffff810faf6b)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/signal.c (ffffffff8110445f)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6b76)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/auditsc.c (ffffffff812316d2)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff81249895)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/ptrace.c (ffffffff81106e9e)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/signal.c (ffffffff811106df)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d9896)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/auditsc.c (ffffffff81248362)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff8125f7a5)
Location: arch/x86/include/asm/syscall.h:121
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/ptrace.c (ffffffff811107ee)
Location: arch/x86/include/asm/syscall.h:119
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/signal.c (ffffffff8111a02f)
Location: arch/x86/include/asm/syscall.h:119
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_seccomp
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef546)
Location: arch/x86/include/asm/syscall.h:119
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
```
In kernel/auditsc.c (ffffffff812621c2)
Location: arch/x86/include/asm/syscall.h:119
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff812797b5)
Location: arch/x86/include/asm/syscall.h:119
Inline: True
Inline callers:
  - kernel/seccomp.c:populate_seccomp_data
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
In kernel/ptrace.c (ffff800010107898)
Location: arch/arm64/include/asm/syscall.h:79
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffff8000101f2e58)
Location: arch/arm64/include/asm/syscall.h:79
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffff800010209474)
Location: arch/arm64/include/asm/syscall.h:79
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (0)
Location: arch/arm/include/asm/syscall.h:76
Inline: True
```
```
In kernel/auditsc.c (0)
Location: arch/arm/include/asm/syscall.h:76
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/arm/include/asm/syscall.h:76
Inline: True
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
In kernel/ptrace.c (c00000000014e0b0)
Location: arch/powerpc/include/asm/syscall.h:104
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (c000000000267800)
Location: arch/powerpc/include/asm/syscall.h:104
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (c000000000286528)
Location: arch/powerpc/include/asm/syscall.h:104
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (0)
Location: arch/riscv/include/asm/syscall.h:83
Inline: True
```
```
In kernel/auditsc.c (0)
Location: arch/riscv/include/asm/syscall.h:83
Inline: True
```
```
In kernel/seccomp.c (0)
Location: arch/riscv/include/asm/syscall.h:83
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
In kernel/ptrace.c (ffffffff810a77d2)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffffffff8117661b)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff8118a0bc)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (ffffffff810961b2)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffffffff811697bb)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff8117d1ec)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (ffffffff810a6d32)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffffffff811743eb)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff81187e8c)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
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
In kernel/ptrace.c (ffffffff810af002)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_get_syscall_info
```
```
In kernel/auditsc.c (ffffffff81181ccb)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_seccomp
  - kernel/auditsc.c:__audit_syscall_entry
```
```
In kernel/seccomp.c (ffffffff811957e0)
Location: arch/x86/include/asm/syscall.h:164
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_init_siginfo
```
</details>
</li>
</ul>

## Differences
