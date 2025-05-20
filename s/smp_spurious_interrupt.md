# Function: <code>smp_spurious_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810541a0)
Location: arch/x86/kernel/apic/apic.c:1830
Inline: False
```
**Symbols:**

```
ffffffff810541a0-ffffffff810541ce: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81054350)
Location: arch/x86/kernel/apic/apic.c:1869
Inline: False
```
**Symbols:**

```
ffffffff81054350-ffffffff8105437e: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81057050)
Location: arch/x86/kernel/apic/apic.c:1867
Inline: False
```
**Symbols:**

```
ffffffff81057050-ffffffff81057079: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8190e9b0)
Location: arch/x86/kernel/apic/apic.c:1943
Inline: False
```
**Symbols:**

```
ffffffff8190e9b0-ffffffff8190e9d9: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81a02e40)
Location: arch/x86/kernel/apic/apic.c:2008
Inline: False
```
**Symbols:**

```
ffffffff81a02e40-ffffffff81a02f54: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81a02570)
Location: arch/x86/kernel/apic/apic.c:2021
Inline: False
```
**Symbols:**

```
ffffffff81a02570-ffffffff81a0268b: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02620)
Location: arch/x86/kernel/apic/apic.c:2029
Inline: False
```
**Symbols:**

```
ffffffff81c02620-ffffffff81c02744: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02870)
Location: arch/x86/kernel/apic/apic.c:2107
Inline: False
```
**Symbols:**

```
ffffffff81c02870-ffffffff81c029be: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c028a0)
Location: arch/x86/kernel/apic/apic.c:2164
Inline: False
```
**Symbols:**

```
ffffffff81c028a0-ffffffff81c029ee: smp_spurious_interrupt (STB_GLOBAL)
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
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02880)
Location: arch/x86/kernel/apic/apic.c:2164
Inline: False
```
**Symbols:**

```
ffffffff81c02880-ffffffff81c029ce: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02730)
Location: arch/x86/kernel/apic/apic.c:2164
Inline: False
```
**Symbols:**

```
ffffffff81c02730-ffffffff81c0287e: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c027f0)
Location: arch/x86/kernel/apic/apic.c:2164
Inline: False
```
**Symbols:**

```
ffffffff81c027f0-ffffffff81c0293e: smp_spurious_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smp_spurious_interrupt(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a70)
Location: arch/x86/kernel/apic/apic.c:2164
Inline: False
```
**Symbols:**

```
ffffffff81c02a70-ffffffff81c02bf3: smp_spurious_interrupt (STB_GLOBAL)
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
