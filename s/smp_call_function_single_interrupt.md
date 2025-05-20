# Function: <code>smp_call_function_single_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81050cd0)
Location: arch/x86/kernel/smp.c:315
Inline: False
```
**Symbols:**

```
ffffffff81050cd0-ffffffff81050d05: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81050e90)
Location: arch/x86/kernel/smp.c:315
Inline: False
```
**Symbols:**

```
ffffffff81050e90-ffffffff81050ec5: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81053740)
Location: arch/x86/kernel/smp.c:317
Inline: False
```
**Symbols:**

```
ffffffff81053740-ffffffff81053775: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (0)
Location: arch/x86/kernel/smp.c:322
Inline: False
```
**Symbols:**

```
ffffffff8190e7c0-ffffffff8190e7d0: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81a02c40)
Location: arch/x86/kernel/smp.c:290
Inline: False
```
**Symbols:**

```
ffffffff81a02c40-ffffffff81a02d08: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81a02370)
Location: arch/x86/kernel/smp.c:291
Inline: False
```
**Symbols:**

```
ffffffff81a02370-ffffffff81a02440: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c02410)
Location: arch/x86/kernel/smp.c:291
Inline: False
```
**Symbols:**

```
ffffffff81c02410-ffffffff81c024e0: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c02660)
Location: arch/x86/kernel/smp.c:289
Inline: False
```
**Symbols:**

```
ffffffff81c02660-ffffffff81c02730: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c02690)
Location: arch/x86/kernel/smp.c:257
Inline: False
```
**Symbols:**

```
ffffffff81c02690-ffffffff81c02760: smp_call_function_single_interrupt (STB_GLOBAL)
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
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c02670)
Location: arch/x86/kernel/smp.c:257
Inline: False
```
**Symbols:**

```
ffffffff81c02670-ffffffff81c02740: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c02520)
Location: arch/x86/kernel/smp.c:257
Inline: False
```
**Symbols:**

```
ffffffff81c02520-ffffffff81c025f0: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c025e0)
Location: arch/x86/kernel/smp.c:257
Inline: False
```
**Symbols:**

```
ffffffff81c025e0-ffffffff81c026b0: smp_call_function_single_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smp_call_function_single_interrupt(struct pt_regs *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smp.c (ffffffff81c02800)
Location: arch/x86/kernel/smp.c:257
Inline: False
```
**Symbols:**

```
ffffffff81c02800-ffffffff81c028f8: smp_call_function_single_interrupt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pt_regs *r</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pt_regs *regs</code>
</li>
</ul>
</details>
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
