# Function: <code>restore_sigcontext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e270)
Location: arch/x86/kernel/signal.c:64
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
```
**Symbols:**

```
ffffffff8102e270-ffffffff8102e3a8: restore_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d000)
Location: arch/x86/kernel/signal.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8102d000-ffffffff8102d18b: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102cea0)
Location: arch/x86/kernel/signal.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8102cea0-ffffffff8102d026: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102b100)
Location: arch/x86/kernel/signal.c:95
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8102b100-ffffffff8102b282: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102be30)
Location: arch/x86/kernel/signal.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8102be30-ffffffff8102bfb5: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d100)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8102d100-ffffffff8102d287: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e350)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8102e350-ffffffff8102e4d7: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810300b0)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810300b0-ffffffff81030237: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810309f0)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810309f0-ffffffff81030b77: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81033a00)
Location: arch/x86/kernel/signal.c:81
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81033a00-ffffffff81033bd6: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81034470)
Location: arch/x86/kernel/signal.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81034470-ffffffff81034646: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81036000)
Location: arch/x86/kernel/signal.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81036000-ffffffff810361d6: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8103b280)
Location: arch/x86/kernel/signal.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8103b280-ffffffff8103b456: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81041980)
Location: arch/x86/kernel/signal.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81041980-ffffffff81041b71: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_64.c (ffffffff8104b890)
Location: arch/x86/kernel/signal_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8104b890-ffffffff8104ba81: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_64.c (ffffffff8104c120)
Location: arch/x86/kernel/signal_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff8104c120-ffffffff8104c311: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *usc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_64.c (ffffffff810533a0)
Location: arch/x86/kernel/signal_64.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810533a0-ffffffff81053591: restore_sigcontext (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/kernel/signal_64.c (c000000000031e20)
Location: arch/powerpc/kernel/signal_64.c:321
Inline: True
Direct callers:
  - arch/powerpc/kernel/signal_64.c:sys_rt_sigreturn
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
```
**Symbols:**

```
c000000000031e20-c0000000000325a0: restore_sigcontext.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/signal.c (ffffffe0000b68e4)
Location: arch/riscv/kernel/signal.c:81
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
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
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030b50)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81030b50-ffffffff81030cd7: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81020580)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81020580-ffffffff810206f8: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810309b0)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff810309b0-ffffffff81030b37: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int restore_sigcontext(struct pt_regs *regs, struct sigcontext_64 *sc, long unsigned int uc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81031840)
Location: arch/x86/kernel/signal.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
```
**Symbols:**

```
ffffffff81031840-ffffffff810319c7: restore_sigcontext (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int uc_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sigcontext_64 *usc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sigcontext_64 *sc</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
