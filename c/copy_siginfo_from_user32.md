# Function: <code>copy_siginfo_from_user32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t *to, compat_siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102ef70)
Location: arch/x86/kernel/signal_compat.c:75
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8102ef70-ffffffff8102efd9: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t *to, compat_siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102e030)
Location: arch/x86/kernel/signal_compat.c:183
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8102e030-ffffffff8102e099: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t *to, compat_siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102df20)
Location: arch/x86/kernel/signal_compat.c:208
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8102df20-ffffffff8102df89: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t *to, compat_siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102c190)
Location: arch/x86/kernel/signal_compat.c:208
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8102c190-ffffffff8102c1f9: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_siginfo_from_user32(siginfo_t *to, compat_siginfo_t *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102cf00)
Location: arch/x86/kernel/signal_compat.c:206
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:C_SYSC_rt_tgsigqueueinfo
  - kernel/signal.c:C_SYSC_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff8102cf00-ffffffff8102cf6c: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a1f00)
Location: kernel/signal.c:2951
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_compat_sys_rt_tgsigqueueinfo
  - kernel/signal.c:__do_compat_sys_rt_sigqueueinfo
```
**Symbols:**

```
ffffffff810a1f00-ffffffff810a20cd: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aad30)
Location: kernel/signal.c:3285
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff810aad30-ffffffff810aad9d: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afdc0)
Location: kernel/signal.c:3414
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810afdc0-ffffffff810afe2f: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b63e0)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810b63e0-ffffffff810b644f: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810be620)
Location: kernel/signal.c:3437
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810be620-ffffffff810be68a: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9920)
Location: kernel/signal.c:3457
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810b9920-ffffffff810b998a: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bb110)
Location: kernel/signal.c:3479
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810bb110-ffffffff810bb17a: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cda20)
Location: kernel/signal.c:3567
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810cda20-ffffffff810cda8a: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e5b80)
Location: kernel/signal.c:3549
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff810e5b80-ffffffff810e5c07: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81106730)
Location: kernel/signal.c:3551
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81106730-ffffffff811067b7: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81112a20)
Location: kernel/signal.c:3575
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff81112a20-ffffffff81112aa7: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8111c410)
Location: kernel/signal.c:3586
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__do_sys_pidfd_send_signal
```
**Symbols:**

```
ffffffff8111c410-ffffffff8111c497: copy_siginfo_from_user32 (STB_GLOBAL)
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
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010112660)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
```
**Symbols:**

```
ffff800010112660-ffff80001011280c: copy_siginfo_from_user32 (STB_GLOBAL)
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
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015a160)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:__se_sys_pidfd_send_signal
```
**Symbols:**

```
c00000000015a160-c00000000015a1f0: copy_siginfo_from_user32 (STB_GLOBAL)
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
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b0750)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810b0750-ffffffff810b07bf: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f070)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff8109f070-ffffffff8109f0df: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810afcb0)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810afcb0-ffffffff810afd1f: copy_siginfo_from_user32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_siginfo_from_user32(struct kernel_siginfo *to, const struct compat_siginfo *ufrom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7f80)
Location: kernel/signal.c:3419
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/signal.c:copy_siginfo_from_user_any
```
**Symbols:**

```
ffffffff810b7f80-ffffffff810b7fef: copy_siginfo_from_user32 (STB_GLOBAL)
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
<b>Param added. </b>
<code>const struct compat_siginfo *ufrom</code>
</li>
<li>
<b>Param removed. </b>
<code>compat_siginfo_t *from</code>
</li>
<li>
<b>Param type changed. </b>
<code>siginfo_t *to</code> ➡️ <code>struct siginfo *to</code>
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
<code>struct siginfo *to</code> ➡️ <code>struct kernel_siginfo *to</code>
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
