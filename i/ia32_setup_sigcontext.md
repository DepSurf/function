# Function: <code>ia32_setup_sigcontext</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81077eb0)
Location: arch/x86/ia32/ia32_signal.c:173
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff81077eb0-ffffffff81077f9d: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81079390)
Location: arch/x86/ia32/ia32_signal.c:173
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81079390-ffffffff81079474: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d180)
Location: arch/x86/ia32/ia32_signal.c:173
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8107d180-ffffffff8107d264: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8107b980)
Location: arch/x86/ia32/ia32_signal.c:174
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8107b980-ffffffff8107ba64: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81082080)
Location: arch/x86/ia32/ia32_signal.c:175
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81082080-ffffffff81082164: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81085740)
Location: arch/x86/ia32/ia32_signal.c:174
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81085740-ffffffff81085824: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c4b0)
Location: arch/x86/ia32/ia32_signal.c:174
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8108c4b0-ffffffff8108c594: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81090390)
Location: arch/x86/ia32/ia32_signal.c:179
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81090390-ffffffff81090474: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81090ef0)
Location: arch/x86/ia32/ia32_signal.c:180
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81090ef0-ffffffff81090fd4: ia32_setup_sigcontext (STB_LOCAL)
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
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8108feb0)
Location: arch/x86/ia32/ia32_signal.c:180
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8108feb0-ffffffff8108ff94: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8107e9c0)
Location: arch/x86/ia32/ia32_signal.c:180
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8107e9c0-ffffffff8107eaa4: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff8108fe60)
Location: arch/x86/ia32/ia32_signal.c:180
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8108fe60-ffffffff8108ff44: ia32_setup_sigcontext (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ia32_setup_sigcontext(struct sigcontext_32 *sc, void *fpstate, struct pt_regs *regs, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/ia32_signal.c (ffffffff81092240)
Location: arch/x86/ia32/ia32_signal.c:180
Inline: False
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81092240-ffffffff81092324: ia32_setup_sigcontext (STB_LOCAL)
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
