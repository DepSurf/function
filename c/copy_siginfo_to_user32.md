# Function: <code>copy_siginfo_to_user32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102ee70)
Location: arch/x86/kernel/signal_compat.c:4
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
  - kernel/compat.c:C_SYSC_waitid
```
**Symbols:**

```
ffffffff8102ee70-ffffffff8102ef6a: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102dec0)
Location: arch/x86/kernel/signal_compat.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
  - kernel/compat.c:C_SYSC_waitid
```
**Symbols:**

```
ffffffff8102dec0-ffffffff8102e023: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102def0)
Location: arch/x86/kernel/signal_compat.c:203
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/compat.c:C_SYSC_rt_sigtimedwait
  - kernel/compat.c:C_SYSC_waitid
```
**Symbols:**

```
ffffffff8102def0-ffffffff8102df1b: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102c160)
Location: arch/x86/kernel/signal_compat.c:203
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
```
**Symbols:**

```
ffffffff8102c160-ffffffff8102c18b: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_siginfo_to_user32(compat_siginfo_t *to, const siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102ced0)
Location: arch/x86/kernel/signal_compat.c:201
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:C_SYSC_rt_sigtimedwait
```
**Symbols:**

```
ffffffff8102ced0-ffffffff8102cefb: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1dc0)
Location: kernel/signal.c:2860
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__do_compat_sys_rt_sigtimedwait
```
**Symbols:**

```
ffffffff810a1dc0-ffffffff810a1deb: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaa00)
Location: kernel/signal.c:3104
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810aaa00-ffffffff810aaa2b: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afa90)
Location: kernel/signal.c:3233
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810afa90-ffffffff810afabb: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b60b0)
Location: kernel/signal.c:3238
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810b60b0-ffffffff810b60db: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81033be0)
Location: arch/x86/kernel/signal.c:531
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff81033be0-ffffffff81033c0d: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81034650)
Location: arch/x86/kernel/signal.c:532
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff81034650-ffffffff8103467d: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810361e0)
Location: arch/x86/kernel/signal.c:548
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810361e0-ffffffff8103620d: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103b460)
Location: arch/x86/kernel/signal.c:553
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x64_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff8103b460-ffffffff8103b48d: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010112238)
Location: kernel/signal.c:3238
Inline: False
Direct callers:
  - arch/arm64/kernel/signal32.c:compat_setup_rt_frame
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__arm64_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffff800010112238-ffff800010112480: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000159cf0)
Location: kernel/signal.c:3238
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__se_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
c000000000159cf0-c000000000159ef4: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
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
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0420)
Location: kernel/signal.c:3238
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810b0420-ffffffff810b044b: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ed40)
Location: kernel/signal.c:3238
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff8109ed40-ffffffff8109ed6b: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af980)
Location: kernel/signal.c:3238
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810af980-ffffffff810af9ab: copy_siginfo_to_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_siginfo_to_user32(struct compat_siginfo *to, const struct kernel_siginfo *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7c50)
Location: kernel/signal.c:3238
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_peek_siginfo
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time32
  - kernel/signal.c:__x32_compat_sys_rt_sigtimedwait_time64
  - kernel/signal.c:__ia32_compat_sys_rt_sigtimedwait_time64
```
**Symbols:**

```
ffffffff810b7c50-ffffffff810b7c7b: copy_siginfo_to_user32 (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
