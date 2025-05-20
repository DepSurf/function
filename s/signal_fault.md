# Function: <code>signal_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102ebd0)
Location: arch/x86/kernel/signal.c:743
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
```
**Symbols:**

```
ffffffff8102ebd0-ffffffff8102eca6: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102dc00)
Location: arch/x86/kernel/signal.c:836
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8102dc00-ffffffff8102dcd6: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102da60)
Location: arch/x86/kernel/signal.c:838
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8102da60-ffffffff8102db36: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102bce0)
Location: arch/x86/kernel/signal.c:839
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8102bce0-ffffffff8102bdb4: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102ca00)
Location: arch/x86/kernel/signal.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8102ca00-ffffffff8102cad4: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:847
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8102dee7-ffffffff8102df5d: signal_fault.cold.15 (STB_LOCAL)
ffffffff8102dcb0-ffffffff8102dd0c: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:847
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff8102f127-ffffffff8102f19d: signal_fault.cold.15 (STB_LOCAL)
ffffffff8102eef0-ffffffff8102ef4c: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:sys32_sigreturn
```
**Symbols:**

```
ffffffff81030ef8-ffffffff81030f6c: signal_fault.cold (STB_LOCAL)
ffffffff81030cc0-ffffffff81030d19: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810317b8-ffffffff81031827: signal_fault.cold (STB_LOCAL)
ffffffff81031580-ffffffff810315d9: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81034018-ffffffff81034087: signal_fault.cold (STB_LOCAL)
ffffffff81033de0-ffffffff81033e39: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81bd3236-ffffffff81bd32a5: signal_fault.cold (STB_LOCAL)
ffffffff81034850-ffffffff810348a9: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:836
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81bc564e-ffffffff81bc56bd: signal_fault.cold (STB_LOCAL)
ffffffff81036310-ffffffff81036369: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:896
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81c98265-ffffffff81c982d4: signal_fault.cold (STB_LOCAL)
ffffffff8103b5b0-ffffffff8103b609: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:900
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81e476fc-ffffffff81e4776b: signal_fault.cold (STB_LOCAL)
ffffffff81042370-ffffffff810423dd: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104b6e0)
Location: arch/x86/kernel/signal.c:337
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff8104b6e0-ffffffff8104b7b6: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104bf70)
Location: arch/x86/kernel/signal.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff8104bf70-ffffffff8104c046: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810531f0)
Location: arch/x86/kernel/signal.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_rt_sigreturn
  - arch/x86/kernel/signal_32.c:__do_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810531f0-ffffffff810532c6: signal_fault (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81031918-ffffffff81031987: signal_fault.cold (STB_LOCAL)
ffffffff810316e0-ffffffff81031739: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff810212f8-ffffffff81021367: signal_fault.cold (STB_LOCAL)
ffffffff810210c0-ffffffff81021119: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81031778-ffffffff810317e7: signal_fault.cold (STB_LOCAL)
ffffffff81031540-ffffffff81031599: signal_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void signal_fault(struct pt_regs *regs, void *frame, char *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:846
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:sys32_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__x64_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__x32_compat_sys_sigreturn
  - arch/x86/ia32/ia32_signal.c:__ia32_compat_sys_sigreturn
```
**Symbols:**

```
ffffffff81032628-ffffffff81032697: signal_fault.cold (STB_LOCAL)
ffffffff810323f0-ffffffff81032449: signal_fault (STB_GLOBAL)
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
