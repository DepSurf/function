# Function: <code>oops_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031b60)
Location: arch/x86/kernel/dumpstack.c:229
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81031b60-ffffffff81031c2a: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030c70)
Location: arch/x86/kernel/dumpstack.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81030c70-ffffffff81030d3c: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030850)
Location: arch/x86/kernel/dumpstack.c:213
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81030850-ffffffff8103091c: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102eb20)
Location: arch/x86/kernel/dumpstack.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8102eb20-ffffffff8102ebe2: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810309f0)
Location: arch/x86/kernel/dumpstack.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810309f0-ffffffff81030ab2: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:340
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81031e0b-ffffffff81031e23: oops_end.cold.10 (STB_LOCAL)
ffffffff81031c00-ffffffff81031ccc: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8103317b-ffffffff81033193: oops_end.cold.10 (STB_LOCAL)
ffffffff81032f00-ffffffff81032fcc: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81034fdd-ffffffff81034ff5: oops_end.cold (STB_LOCAL)
ffffffff81034d10-ffffffff81034dd2: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8103580d-ffffffff81035825: oops_end.cold (STB_LOCAL)
ffffffff81035540-ffffffff81035602: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810378ba-ffffffff810378d2: oops_end.cold (STB_LOCAL)
ffffffff810373b0-ffffffff81037474: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81bd3496-ffffffff81bd34ae: oops_end.cold (STB_LOCAL)
ffffffff81038470-ffffffff8103853b: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81bc5909-ffffffff81bc5921: oops_end.cold (STB_LOCAL)
ffffffff81039fb0-ffffffff8103a07f: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81c98653-ffffffff81c9866b: oops_end.cold (STB_LOCAL)
ffffffff8103f960-ffffffff8103fa2f: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81e47b82-ffffffff81e47b9a: oops_end.cold (STB_LOCAL)
ffffffff810470c0-ffffffff8104719e: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810512f0)
Location: arch/x86/kernel/dumpstack.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810512f0-ffffffff810513e2: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052050)
Location: arch/x86/kernel/dumpstack.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81052050-ffffffff81052142: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059270)
Location: arch/x86/kernel/dumpstack.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81059270-ffffffff81059362: oops_end (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c030f420)
Location: arch/arm/kernel/traps.c:321
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:die
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002c6b0)
Location: arch/powerpc/kernel/traps.c:207
Inline: True
Direct callers:
  - arch/powerpc/kernel/traps.c:die
```
**Symbols:**

```
c00000000002c6b0-c00000000002c844: oops_end (STB_LOCAL)
```
</details>
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
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8103596d-ffffffff81035985: oops_end.cold (STB_LOCAL)
ffffffff810356a0-ffffffff81035762: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810252bd-ffffffff810252d5: oops_end.cold (STB_LOCAL)
ffffffff81025000-ffffffff810250ba: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810357cd-ffffffff810357e5: oops_end.cold (STB_LOCAL)
ffffffff81035500-ffffffff810355c2: oops_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void oops_end(long unsigned int flags, struct pt_regs *regs, int signr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810367ad-ffffffff810367c5: oops_end.cold (STB_LOCAL)
ffffffff810364e0-ffffffff810365a2: oops_end (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
