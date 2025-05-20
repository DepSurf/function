# Function: <code>set_current_blocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090a40)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:SyS_ssetmask
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - kernel/compat.c:compat_SyS_sigprocmask
  - kernel/compat.c:compat_SyS_sigprocmask
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
```
**Symbols:**

```
ffffffff81090a40-ffffffff81090a57: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093bd1)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - kernel/compat.c:compat_SyS_sigprocmask
  - kernel/compat.c:compat_SyS_sigprocmask
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff81093ae0-ffffffff81093af7: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098bd1)
Location: kernel/signal.c:2484
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - kernel/compat.c:compat_SyS_sigprocmask
  - kernel/compat.c:compat_SyS_sigprocmask
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff81098ae0-ffffffff81098af7: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095e61)
Location: kernel/signal.c:2505
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - kernel/compat.c:compat_SyS_sigprocmask
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff81095d70-ffffffff81095d87: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ccb1)
Location: kernel/signal.c:2506
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:SyS_ssetmask
  - kernel/signal.c:SyS_sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - kernel/compat.c:compat_SyS_sigprocmask
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:compat_SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
  - fs/eventpoll.c:SyS_epoll_pwait
```
**Symbols:**

```
ffffffff8109cbc0-ffffffff8109cbd7: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1271)
Location: kernel/signal.c:2639
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__x32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_compat_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__ia32_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
  - fs/eventpoll.c:__x64_sys_epoll_pwait
```
**Symbols:**

```
ffffffff810a0fa0-ffffffff810a0fb7: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a97f1)
Location: kernel/signal.c:2738
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810a93e0-ffffffff810a93f7: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac081)
Location: kernel/signal.c:2897
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810abe60-ffffffff810abe77: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2691)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810b2470-ffffffff810b2487: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb111)
Location: kernel/signal.c:2920
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810baf30-ffffffff810baf8e: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b63c1)
Location: kernel/signal.c:2940
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810b61e0-ffffffff810b623e: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5663)
Location: kernel/signal.c:2962
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810b7de0-ffffffff810b7e3e: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c7c63)
Location: kernel/signal.c:3047
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__x64_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810ca270-ffffffff810ca2ce: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810def43)
Location: kernel/signal.c:3027
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810e1dc0-ffffffff810e1e22: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ffce3)
Location: kernel/signal.c:3029
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff81102110-ffffffff81102172: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110bd73)
Location: kernel/signal.c:3053
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff8110e350-ffffffff8110e3b2: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81115723)
Location: kernel/signal.c:3064
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff81117cd0-ffffffff81117d32: set_current_blocked (STB_GLOBAL)
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
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010e4bc)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__arm64_sys_ssetmask
  - kernel/signal.c:__arm64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - kernel/compat.c:__arm64_compat_sys_sigprocmask
```
**Symbols:**

```
ffff80001010e200-ffff80001010e240: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03665ac)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/arm/kernel/signal.c:restore_sigframe
```
**Symbols:**

```
c0366540-c036656c: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155904)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:__se_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/powerpc/kernel/signal_32.c:compat_sys_sigreturn
  - arch/powerpc/kernel/signal_32.c:compat_sys_rt_sigreturn
  - arch/powerpc/kernel/signal_32.c:do_setcontext
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
  - kernel/compat.c:__se_compat_sys_sigprocmask
```
**Symbols:**

```
c000000000155690-c0000000001556b8: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1eda)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigsuspend
  - kernel/signal.c:__se_sys_ssetmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffe0000cf15a-ffffffe0000cf192: set_current_blocked (STB_GLOBAL)
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
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aca01)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810ac7e0-ffffffff810ac7f7: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b381)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff8109b160-ffffffff8109b177: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abf61)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810abd40-ffffffff810abd57: set_current_blocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_current_blocked(sigset_t *newset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b40d1)
Location: kernel/signal.c:2902
Inline: True
Inline callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:signal_setup_done
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
  - kernel/compat.c:__x32_compat_sys_sigprocmask
  - kernel/compat.c:__ia32_compat_sys_sigprocmask
```
**Symbols:**

```
ffffffff810b3eb0-ffffffff810b3ec7: set_current_blocked (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
