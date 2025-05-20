# Function: <code>ptrace_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810901b0)
Location: kernel/signal.c:1913
Inline: True
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - arch/x86/entry/common.c:syscall_trace_enter_phase2
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:seccomp_phase2
```
**Symbols:**

```
ffffffff810901b0-ffffffff81090236: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093220)
Location: kernel/signal.c:1913
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81093220-ffffffff810932a6: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810981b0)
Location: kernel/signal.c:1919
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810981b0-ffffffff81098236: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810954a0)
Location: kernel/signal.c:1941
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810954a0-ffffffff81095526: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c340)
Location: kernel/signal.c:1942
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8109c340-ffffffff8109c3c6: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a0730)
Location: kernel/signal.c:2074
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_trace_enter
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a0730-ffffffff810a07b6: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a8a40)
Location: kernel/signal.c:2164
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810a8a40-ffffffff810a8ac6: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad290)
Location: kernel/signal.c:2266
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810ad290-ffffffff810ad308: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b38b0)
Location: kernel/signal.c:2271
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810b38b0-ffffffff810b3928: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc2f0)
Location: kernel/signal.c:2271
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff810bc2f0-ffffffff810bc368: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b75e0)
Location: kernel/signal.c:2272
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/entry/common.c:syscall_exit_work
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff810b75e0-ffffffff810b7658: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8be0)
Location: kernel/signal.c:2284
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/entry/common.c:syscall_exit_work
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff810b8be0-ffffffff810b8c58: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb170)
Location: kernel/signal.c:2366
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/entry/common.c:syscall_exit_work
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff810cb170-ffffffff810cb1e8: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e4600)
Location: kernel/signal.c:2347
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/entry/common.c:syscall_exit_work
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff810e4600-ffffffff810e4689: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104c60)
Location: kernel/signal.c:2348
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/entry/common.c:syscall_exit_work
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff81104c60-ffffffff81104ce9: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110ee0)
Location: kernel/signal.c:2370
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/entry/common.c:syscall_exit_work
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff81110ee0-ffffffff81110f69: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptrace_notify(int exit_code, long unsigned int message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111a850)
Location: kernel/signal.c:2384
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/entry/common.c:syscall_exit_work
  - kernel/entry/common.c:syscall_trace_enter
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:exec_binprm
```
**Symbols:**

```
ffffffff8111a850-ffffffff8111a8d9: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010f7e8)
Location: kernel/signal.c:2271
Inline: True
Direct callers:
  - arch/arm64/kernel/ptrace.c:syscall_trace_exit
  - arch/arm64/kernel/ptrace.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffff80001010f7e8-ffff80001010f8b0: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036754c)
Location: kernel/signal.c:2271
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:syscall_trace_exit
  - arch/arm/kernel/ptrace.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
c036754c-c03675f8: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000156d30)
Location: kernel/signal.c:2271
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c000000000156d30-c000000000156e10: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cfc1c)
Location: kernel/signal.c:2271
Inline: True
Direct callers:
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_exit
  - arch/riscv/kernel/ptrace.c:do_syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffe0000cfc1c-ffffffe0000cfcbe: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810adc20)
Location: kernel/signal.c:2271
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810adc20-ffffffff810adc98: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c590)
Location: kernel/signal.c:2271
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8109c590-ffffffff8109c602: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad180)
Location: kernel/signal.c:2271
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810ad180-ffffffff810ad1f8: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ptrace_notify(int exit_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5340)
Location: kernel/signal.c:2271
Inline: True
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
  - arch/x86/entry/common.c:syscall_trace_enter
  - kernel/fork.c:_do_fork
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:signal_setup_done
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff810b5340-ffffffff810b53af: ptrace_notify (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int message</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
