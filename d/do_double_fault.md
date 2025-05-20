# Function: <code>do_double_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102fb20)
Location: arch/x86/kernel/traps.c:312
Inline: False
```
**Symbols:**

```
ffffffff8102fb20-ffffffff8102fc1a: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102ebc0)
Location: arch/x86/kernel/traps.c:297
Inline: False
```
**Symbols:**

```
ffffffff8102ebc0-ffffffff8102ecb2: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102eb50)
Location: arch/x86/kernel/traps.c:312
Inline: False
```
**Symbols:**

```
ffffffff8102eb50-ffffffff8102ec75: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102ce60)
Location: arch/x86/kernel/traps.c:347
Inline: False
```
**Symbols:**

```
ffffffff8102ce60-ffffffff8102cf85: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102dc20)
Location: arch/x86/kernel/traps.c:339
Inline: False
```
**Symbols:**

```
ffffffff8102dc20-ffffffff8102dd46: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:340
Inline: False
```
**Symbols:**

```
ffffffff8102efaa-ffffffff8102efbc: do_double_fault.cold.14 (STB_LOCAL)
ffffffff8102ebb0-ffffffff8102eccc: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:315
Inline: False
```
**Symbols:**

```
ffffffff81030239-ffffffff8103024b: do_double_fault.cold.16 (STB_LOCAL)
ffffffff8102fde0-ffffffff8102fefc: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code, long unsigned int cr2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:316
Inline: False
```
**Symbols:**

```
ffffffff81031ffb-ffffffff8103200d: do_double_fault.cold (STB_LOCAL)
ffffffff81031bb0-ffffffff81031cb6: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code, long unsigned int cr2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:316
Inline: False
```
**Symbols:**

```
ffffffff810328bb-ffffffff810328cd: do_double_fault.cold (STB_LOCAL)
ffffffff81032470-ffffffff81032576: do_double_fault (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code, long unsigned int cr2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:316
Inline: False
```
**Symbols:**

```
ffffffff81032a1b-ffffffff81032a2d: do_double_fault.cold (STB_LOCAL)
ffffffff810325d0-ffffffff810326d6: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code, long unsigned int cr2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:316
Inline: False
```
**Symbols:**

```
ffffffff81022374-ffffffff81022386: do_double_fault.cold (STB_LOCAL)
ffffffff81021f30-ffffffff81022036: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code, long unsigned int cr2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:316
Inline: False
```
**Symbols:**

```
ffffffff8103287b-ffffffff8103288d: do_double_fault.cold (STB_LOCAL)
ffffffff81032430-ffffffff81032536: do_double_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void do_double_fault(struct pt_regs *regs, long int error_code, long unsigned int cr2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/traps.c (0)
Location: arch/x86/kernel/traps.c:316
Inline: False
```
**Symbols:**

```
ffffffff810337db-ffffffff810337ed: do_double_fault.cold (STB_LOCAL)
ffffffff81033370-ffffffff81033481: do_double_fault (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cr2</code>
</li>
</ul>
</details>
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
