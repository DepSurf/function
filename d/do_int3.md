# Function: <code>do_int3</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f7b0)
Location: arch/x86/kernel/traps.c:484
Inline: True
```
**Symbols:**

```
ffffffff8102f7b0-ffffffff8102f8e9: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e8b0)
Location: arch/x86/kernel/traps.c:469
Inline: True
```
**Symbols:**

```
ffffffff8102e8b0-ffffffff8102e9c7: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e7f0)
Location: arch/x86/kernel/traps.c:530
Inline: True
```
**Symbols:**

```
ffffffff8102e7f0-ffffffff8102e907: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102cb80)
Location: arch/x86/kernel/traps.c:565
Inline: True
```
**Symbols:**

```
ffffffff8102cb80-ffffffff8102cc9e: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102d830)
Location: arch/x86/kernel/traps.c:580
Inline: True
```
**Symbols:**

```
ffffffff8102d830-ffffffff8102d93b: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102e7f0)
Location: arch/x86/kernel/traps.c:581
Inline: True
```
**Symbols:**

```
ffffffff8102e7f0-ffffffff8102e8fa: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102f9c0)
Location: arch/x86/kernel/traps.c:572
Inline: True
```
**Symbols:**

```
ffffffff8102f9c0-ffffffff8102fad5: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810317b0)
Location: arch/x86/kernel/traps.c:569
Inline: True
```
**Symbols:**

```
ffffffff810317b0-ffffffff810318c5: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032070)
Location: arch/x86/kernel/traps.c:569
Inline: True
```
**Symbols:**

```
ffffffff81032070-ffffffff81032185: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81034320)
Location: arch/x86/kernel/traps.c:601
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff81034320-ffffffff8103439e: do_int3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81034d30)
Location: arch/x86/kernel/traps.c:609
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff81034d30-ffffffff81034dae: do_int3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81036790)
Location: arch/x86/kernel/traps.c:610
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff81036790-ffffffff8103680e: do_int3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8103b930)
Location: arch/x86/kernel/traps.c:644
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff8103b930-ffffffff8103b9ae: do_int3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810428d0)
Location: arch/x86/kernel/traps.c:780
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff810428d0-ffffffff81042971: do_int3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104c360)
Location: arch/x86/kernel/traps.c:789
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff8104c360-ffffffff8104c401: do_int3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104cbd0)
Location: arch/x86/kernel/traps.c:790
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff8104cbd0-ffffffff8104cc71: do_int3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool do_int3(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81053e50)
Location: arch/x86/kernel/traps.c:704
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_int3
```
**Symbols:**

```
ffffffff81053e50-ffffffff81053ef1: do_int3 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810321d0)
Location: arch/x86/kernel/traps.c:569
Inline: True
```
**Symbols:**

```
ffffffff810321d0-ffffffff810322e5: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810218a0)
Location: arch/x86/kernel/traps.c:569
Inline: True
```
**Symbols:**

```
ffffffff810218a0-ffffffff810219a7: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032030)
Location: arch/x86/kernel/traps.c:569
Inline: True
```
**Symbols:**

```
ffffffff81032030-ffffffff81032145: do_int3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void do_int3(struct pt_regs *regs, long int error_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032f30)
Location: arch/x86/kernel/traps.c:569
Inline: True
```
**Symbols:**

```
ffffffff81032f30-ffffffff81033053: do_int3 (STB_GLOBAL)
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
<b>Param removed. </b>
<code>long int error_code</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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
