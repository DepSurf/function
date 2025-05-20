# Function: <code>__copy_siginfo_to_user32</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102dd90)
Location: arch/x86/kernel/signal_compat.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff8102dd90-ffffffff8102dee2: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102c010)
Location: arch/x86/kernel/signal_compat.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff8102c010-ffffffff8102c15e: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102cd30)
Location: arch/x86/kernel/signal_compat.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff8102cd30-ffffffff8102cec1: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1c00)
Location: kernel/signal.c:2866
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810a1c00-ffffffff810a1db5: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa810)
Location: kernel/signal.c:3110
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810aa810-ffffffff810aa9f9: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af8a0)
Location: kernel/signal.c:3239
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810af8a0-ffffffff810afa85: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5ec0)
Location: kernel/signal.c:3244
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810b5ec0-ffffffff810b60a5: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810be5b0)
Location: kernel/signal.c:3336
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff810be5b0-ffffffff810be619: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b98b0)
Location: kernel/signal.c:3356
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff810b98b0-ffffffff810b9919: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb0a0)
Location: kernel/signal.c:3381
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff810bb0a0-ffffffff810bb106: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cd9b0)
Location: kernel/signal.c:3469
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:copy_siginfo_to_user32
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff810cd9b0-ffffffff810cda16: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e58f0)
Location: kernel/signal.c:3450
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810e58f0-ffffffff810e5973: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81106470)
Location: kernel/signal.c:3452
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff81106470-ffffffff811064f3: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81112760)
Location: kernel/signal.c:3476
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff81112760-ffffffff811127e3: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111c150)
Location: kernel/signal.c:3487
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff8111c150-ffffffff8111c1d3: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0230)
Location: kernel/signal.c:3244
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810b0230-ffffffff810b0415: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109eb50)
Location: kernel/signal.c:3244
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff8109eb50-ffffffff8109ed35: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af790)
Location: kernel/signal.c:3244
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810af790-ffffffff810af975: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from, bool x32_ABI);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7a60)
Location: kernel/signal.c:3244
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/signal.c:copy_siginfo_to_user32
```
**Symbols:**

```
ffffffff810b7a60-ffffffff810b7c45: __copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>compat_siginfo_t *to</code> ➡️ <code>struct compat_siginfo *to</code>
</li>
<li>
<b>Param type changed. </b>
<code>const siginfo_t *from</code> ➡️ <code>const struct siginfo *from</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct siginfo *from</code> ➡️ <code>const struct kernel_siginfo *from</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool x32_ABI</code>
</li>
</ul>
</details>
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
