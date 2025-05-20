# Function: <code>sigdelsetmask</code>

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
In kernel/ptrace.c (ffffffff8108c016)
Location: include/linux/signal.h:178
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff81090a45)
Location: include/linux/signal.h:178
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_ssetmask
```
```
In kernel/compat.c (ffffffff81110a83)
Location: include/linux/signal.h:178
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
```
In fs/select.c (ffffffff81221d3d)
Location: include/linux/signal.h:178
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_ppoll
```
```
In fs/signalfd.c (0)
Location: include/linux/signal.h:178
Inline: True
```
```
In fs/compat.c (ffffffff812656fd)
Location: include/linux/signal.h:178
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
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
In kernel/ptrace.c (ffffffff8108efa2)
Location: include/linux/signal.h:193
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff81093bd1)
Location: include/linux/signal.h:193
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/signal.c:signal_setup_done
```
```
In kernel/compat.c (ffffffff811181c3)
Location: include/linux/signal.h:193
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
```
In fs/select.c (ffffffff8124a2e2)
Location: include/linux/signal.h:193
Inline: True
Inline callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/signalfd.c (ffffffff81280604)
Location: include/linux/signal.h:193
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/compat.c (ffffffff81291bff)
Location: include/linux/signal.h:193
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
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
In kernel/ptrace.c (ffffffff81093f32)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff81098bd1)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/signal.c:signal_setup_done
```
```
In kernel/compat.c (ffffffff8111f8e3)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
```
In fs/select.c (ffffffff8125d2a2)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/signalfd.c (ffffffff81294174)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
```
```
In fs/compat.c (ffffffff812a697f)
Location: include/linux/signal.h:210
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
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
In kernel/ptrace.c (ffffffff81091013)
Location: include/linux/signal.h:188
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff81095e61)
Location: include/linux/signal.h:188
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/signal.c:signal_setup_done
```
```
In kernel/compat.c (ffffffff81120c14)
Location: include/linux/signal.h:188
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
```
In fs/select.c (ffffffff8126ab98)
Location: include/linux/signal.h:188
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/signalfd.c (ffffffff812a144c)
Location: include/linux/signal.h:188
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
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
In kernel/ptrace.c (ffffffff81097e83)
Location: include/linux/signal.h:203
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109ccb1)
Location: include/linux/signal.h:203
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:compat_SyS_rt_sigprocmask
  - kernel/signal.c:SyS_rt_sigprocmask
  - kernel/signal.c:signal_setup_done
```
```
In kernel/compat.c (ffffffff8112c2f4)
Location: include/linux/signal.h:203
Inline: True
Inline callers:
  - kernel/compat.c:compat_SyS_sigprocmask
```
```
In fs/select.c (ffffffff8128d40f)
Location: include/linux/signal.h:203
Inline: True
Inline callers:
  - fs/select.c:compat_SyS_ppoll
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
```
```
In fs/signalfd.c (ffffffff812c4779)
Location: include/linux/signal.h:203
Inline: True
Inline callers:
  - fs/signalfd.c:compat_SyS_signalfd
  - fs/signalfd.c:SyS_signalfd
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
In kernel/ptrace.c (ffffffff8109b8cb)
Location: include/linux/signal.h:205
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810a1271)
Location: include/linux/signal.h:205
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:signal_setup_done
```
```
In kernel/compat.c (ffffffff8113a7d3)
Location: include/linux/signal.h:205
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/select.c (ffffffff812b387e)
Location: include/linux/signal.h:205
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:do_pselect
```
```
In fs/signalfd.c (ffffffff812ed2e9)
Location: include/linux/signal.h:205
Inline: True
```
```
In fs/aio.c (ffffffff812f38c1)
Location: include/linux/signal.h:205
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_compat_sys_io_pgetevents
  - fs/aio.c:__ia32_sys_io_pgetevents
  - fs/aio.c:__x64_sys_io_pgetevents
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
In kernel/ptrace.c (ffffffff810a3adf)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810a97f1)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff81146043)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff81301949)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffff810a8895)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810ac081)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff81151414)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff81322eae)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffff810aeeaf)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b2691)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff8115d064)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff81335c0e)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffff810b6a49)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810bb111)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff8116db97)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8136f8ab)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (ffffffff810b1b37)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b63c1)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff8116a16c)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8137d60b)
Location: include/linux/signal.h:223
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (ffffffff810b31e4)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b5663)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff8116ae3c)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8138428b)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (ffffffff810c5384)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810c7c63)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__x64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff81190a3c)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/compat.c:__x64_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff813d152b)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (ffffffff810dc972)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810def43)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/compat.c (ffffffff811c023d)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8145a7c0)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (ffffffff810fcae5)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810ffce3)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/compat.c (ffffffff812025fd)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff814e9d10)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (ffffffff81108b06)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8110bd73)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/compat.c (ffffffff812179d6)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff81520ab0)
Location: include/linux/signal.h:224
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (ffffffff81112496)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff81115723)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal_locked
```
```
In kernel/compat.c (ffffffff8122f596)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff815550c0)
Location: include/linux/signal.h:225
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In arch/arm64/kernel/signal32.c (ffff80001009f294)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
```
```
In virt/kvm/kvm_main.c (ffff8000100b9520)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
```
```
In kernel/ptrace.c (ffff80001010951c)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffff80001010e4bc)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__arm64_sys_ssetmask
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__arm64_compat_sys_rt_sigprocmask
  - kernel/signal.c:__arm64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffff8000101cc894)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffff8000103f35bc)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (c03631bc)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (c03665ac)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In fs/signalfd.c (c05c89c0)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
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
In kernel/ptrace.c (c000000000150aec)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (c000000000155904)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigprocmask
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (c000000000236b10)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__se_compat_sys_sigprocmask
```
```
In fs/signalfd.c (c0000000004fb4bc)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffe0000cc93c)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffe0000d1eda)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:__se_sys_rt_sigprocmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In fs/signalfd.c (ffffffe0002a4fa2)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffff810a921f)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810aca01)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff81155684)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8132e1ee)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffff81097be9)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff8109b381)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff811489a4)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8131ee4e)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffff810a877f)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810abf61)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff81153454)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8132bcbe)
Location: include/linux/signal.h:215
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
In kernel/ptrace.c (ffffffff810b08ad)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
```
In kernel/signal.c (ffffffff810b40d1)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_compat_sys_rt_sigprocmask
  - kernel/signal.c:__ia32_sys_rt_sigprocmask
  - kernel/signal.c:__x64_sys_rt_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:__send_signal
```
```
In kernel/compat.c (ffffffff81160354)
Location: include/linux/signal.h:215
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
```
In fs/signalfd.c (ffffffff8133e96e)
Location: include/linux/signal.h:215
Inline: True
```
</details>
</li>
</ul>

## Differences
