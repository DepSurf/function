# Function: <code>__set_task_blocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108e040)
Location: kernel/signal.c:2459
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
  - kernel/signal.c:do_sigtimedwait
```
**Symbols:**

```
ffffffff8108e040-ffffffff8108e0d3: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810910c0)
Location: kernel/signal.c:2459
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff810910c0-ffffffff81091156: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096030)
Location: kernel/signal.c:2465
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff81096030-ffffffff810960c1: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093010)
Location: kernel/signal.c:2486
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff81093010-ffffffff810930a1: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099ef0)
Location: kernel/signal.c:2487
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff81099ef0-ffffffff81099f81: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109def0)
Location: kernel/signal.c:2620
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff8109def0-ffffffff8109df7f: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a6200)
Location: kernel/signal.c:2719
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff810a6200-ffffffff810a628f: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaef0)
Location: kernel/signal.c:2878
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff810aaef0-ffffffff810aaf84: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b14f0)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff810b14f0-ffffffff810b1584: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8510)
Location: kernel/signal.c:2901
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:do_sigtimedwait
```
**Symbols:**

```
ffffffff810b8510-ffffffff810b8578: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b37c0)
Location: kernel/signal.c:2921
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:do_sigtimedwait
```
**Symbols:**

```
ffffffff810b37c0-ffffffff810b3828: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4ce0)
Location: kernel/signal.c:2943
Inline: False
Direct callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff810b4ce0-ffffffff810b4d48: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6f80)
Location: kernel/signal.c:3028
Inline: False
Direct callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
```
**Symbols:**

```
ffffffff810c6f80-ffffffff810c6fe8: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810debc0)
Location: kernel/signal.c:3008
Inline: False
Direct callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff810debc0-ffffffff810dec34: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ff270)
Location: kernel/signal.c:3010
Inline: False
Direct callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff810ff270-ffffffff810ff2e4: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110b2c0)
Location: kernel/signal.c:3034
Inline: False
Direct callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff8110b2c0-ffffffff8110b334: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81114920)
Location: kernel/signal.c:3045
Inline: False
Direct callers:
  - kernel/signal.c:sigsuspend
  - kernel/signal.c:__ia32_sys_ssetmask
  - kernel/signal.c:__x64_sys_ssetmask
  - kernel/signal.c:__ia32_sys_sigprocmask
  - kernel/signal.c:__x64_sys_sigprocmask
  - kernel/signal.c:set_compat_user_sigmask
  - kernel/signal.c:set_user_sigmask
  - kernel/signal.c:sigprocmask
  - kernel/signal.c:signal_setup_done
```
**Symbols:**

```
ffffffff81114920-ffffffff8111499d: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010d128)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffff80001010d128-ffff80001010d1c8: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03653a0)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
c03653a0-c036546c: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000154200)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
c000000000154200-c0000000001542b8: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce652)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffe0000ce652-ffffffe0000ce6be: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab860)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff810ab860-ffffffff810ab8f4: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a200)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff8109a200-ffffffff8109a294: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aadc0)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff810aadc0-ffffffff810aae54: __set_task_blocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __set_task_blocked(struct task_struct *tsk, const sigset_t *newset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2ea0)
Location: kernel/signal.c:2883
Inline: False
Direct callers:
  - kernel/signal.c:__set_current_blocked
```
**Symbols:**

```
ffffffff810b2ea0-ffffffff810b2f34: __set_task_blocked (STB_LOCAL)
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
