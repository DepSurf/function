# Function: <code>setup_sigcontext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e3b0)
Location: arch/x86/kernel/signal.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8102e3b0-ffffffff8102e4df: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d350)
Location: arch/x86/kernel/signal.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8102d350-ffffffff8102d485: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d1f0)
Location: arch/x86/kernel/signal.c:157
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8102d1f0-ffffffff8102d325: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102b460)
Location: arch/x86/kernel/signal.c:158
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8102b460-ffffffff8102b595: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102c190)
Location: arch/x86/kernel/signal.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8102c190-ffffffff8102c2c5: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d450)
Location: arch/x86/kernel/signal.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8102d450-ffffffff8102d585: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e6a0)
Location: arch/x86/kernel/signal.c:160
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff8102e6a0-ffffffff8102e7d5: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030440)
Location: arch/x86/kernel/signal.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
**Symbols:**

```
ffffffff81030440-ffffffff81030575: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030d80)
Location: arch/x86/kernel/signal.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81030d80-ffffffff81030eb5: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In arch/powerpc/kernel/signal_64.c (c000000000031930)
Location: arch/powerpc/kernel/signal_64.c:91
Inline: True
Direct callers:
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
  - arch/powerpc/kernel/signal_64.c:__se_sys_swapcontext
```
**Symbols:**

```
c000000000031930-c000000000031e18: setup_sigcontext.constprop.0 (STB_LOCAL)
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
In arch/riscv/kernel/signal.c (ffffffe0000b669c)
Location: arch/riscv/kernel/signal.c:133
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
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
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030ee0)
Location: arch/x86/kernel/signal.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81030ee0-ffffffff81031015: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81020900)
Location: arch/x86/kernel/signal.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81020900-ffffffff81020a35: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030d40)
Location: arch/x86/kernel/signal.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81030d40-ffffffff81030e75: setup_sigcontext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int setup_sigcontext(struct sigcontext_64 *sc, void *fpstate, struct pt_regs *regs, long unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81031bd0)
Location: arch/x86/kernel/signal.c:159
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
**Symbols:**

```
ffffffff81031bd0-ffffffff81031d05: setup_sigcontext (STB_GLOBAL)
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
