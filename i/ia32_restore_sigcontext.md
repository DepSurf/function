# Function: <code>ia32_restore_sigcontext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81077fa0)
Location: arch/x86/ia32/ia32_signal.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff81077fa0-ffffffff8107811e: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81079480)
Location: arch/x86/ia32/ia32_signal.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff81079480-ffffffff810795fa: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d270)
Location: arch/x86/ia32/ia32_signal.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8107d270-ffffffff8107d3e1: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ba70)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8107ba70-ffffffff8107bbe1: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81082170)
Location: arch/x86/ia32/ia32_signal.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff81082170-ffffffff810822e4: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81085830)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff81085830-ffffffff810859a4: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c5a0)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8108c5a0-ffffffff8108c714: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81090590)
Location: arch/x86/ia32/ia32_signal.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff81090590-ffffffff8109070d: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff810910f0)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810910f0-ffffffff8109126d: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff810968d0)
Location: arch/x86/ia32/ia32_signal.c:60
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810968d0-ffffffff81096a2c: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81095af0)
Location: arch/x86/ia32/ia32_signal.c:60
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81095af0-ffffffff81095c4c: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81096450)
Location: arch/x86/ia32/ia32_signal.c:60
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81096450-ffffffff810965ac: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff810a63f0)
Location: arch/x86/ia32/ia32_signal.c:60
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810a63f0-ffffffff810a654c: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb670)
Location: arch/x86/ia32/ia32_signal.c:59
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810bb670-ffffffff810bb79c: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_32.c (ffffffff81055720)
Location: arch/x86/kernel/signal_32.c:74
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81055720-ffffffff8105584c: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_32.c (ffffffff81056750)
Location: arch/x86/kernel/signal_32.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81056750-ffffffff8105687c: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *usc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_32.c (ffffffff8105d9a0)
Location: arch/x86/kernel/signal_32.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff8105d9a0-ffffffff8105dacc: ia32_restore_sigcontext (STB_LOCAL)
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
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff810900b0)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810900b0-ffffffff8109022d: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8107ebc0)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff8107ebc0-ffffffff8107ed38: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81090060)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81090060-ffffffff810901dd: ia32_restore_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ia32_restore_sigcontext(struct pt_regs *regs, struct sigcontext_32 *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81092440)
Location: arch/x86/ia32/ia32_signal.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81092440-ffffffff810925bd: ia32_restore_sigcontext (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sigcontext_32 *usc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sigcontext_32 *sc</code>
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
