# Function: <code>arch_smt_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82894e3c)
Location: arch/x86/kernel/cpu/bugs.c:613
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81044db0-ffffffff81044e5c: arch_smt_update.part.4 (STB_LOCAL)
ffffffff81045739-ffffffff81045774: arch_smt_update.part.4.cold.7 (STB_LOCAL)
ffffffff810450a0-ffffffff810450ba: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047b07)
Location: arch/x86/kernel/cpu/bugs.c:790
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81047efd-ffffffff81047f50: arch_smt_update.cold (STB_LOCAL)
ffffffff81047ac0-ffffffff81047be4: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810477b0)
Location: arch/x86/kernel/cpu/common.c:1996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff810477b0-ffffffff810477c0: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104b510)
Location: arch/x86/kernel/cpu/common.c:1954
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff8104b510-ffffffff8104b520: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104abe0)
Location: arch/x86/kernel/cpu/common.c:2049
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff8104abe0-ffffffff8104abf0: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104c4c0)
Location: arch/x86/kernel/cpu/common.c:2053
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff8104c4c0-ffffffff8104c4d0: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81053770)
Location: arch/x86/kernel/cpu/common.c:2095
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81053770-ffffffff81053780: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105f100)
Location: arch/x86/kernel/cpu/common.c:2343
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff8105f100-ffffffff8105f114: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d880)
Location: arch/x86/kernel/cpu/common.c:2354
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff8106d880-ffffffff8106d894: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8369eba3)
Location: arch/x86/kernel/cpu/common.c:2330
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:arch_cpu_finalize_init
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff8106f190-ffffffff8106f1a4: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff838ce89b)
Location: arch/x86/kernel/cpu/common.c:2374
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:arch_cpu_finalize_init
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81076550-ffffffff81076564: arch_smt_update (STB_GLOBAL)
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
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:388
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffff8000100f9320-ffff8000100f9338: arch_smt_update (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:388
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
c0357630-c0357648: arch_smt_update (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001400c0)
Location: kernel/cpu.c:388
Inline: False
Direct callers:
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
c0000000001400c0-c0000000001400cc: arch_smt_update (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3df2)
Location: kernel/cpu.c:388
Inline: False
Direct callers:
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffe0000c3df2-ffffffe0000c3e0c: arch_smt_update (STB_WEAK)
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
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047920)
Location: arch/x86/kernel/cpu/common.c:1996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81047920-ffffffff81047930: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81036c20)
Location: arch/x86/kernel/cpu/common.c:1996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81036c20-ffffffff81036c30: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047760)
Location: arch/x86/kernel/cpu/common.c:1996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81047760-ffffffff81047770: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_smt_update();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81048b70)
Location: arch/x86/kernel/cpu/common.c:1996
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:_cpu_up
  - kernel/cpu.c:_cpu_down
```
**Symbols:**

```
ffffffff81048b70-ffffffff81048b80: arch_smt_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
