# Function: <code>__die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031c80)
Location: arch/x86/kernel/dumpstack.c:254
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81031c80-ffffffff81031d52: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030f60)
Location: arch/x86/kernel/dumpstack.c:275
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81030f60-ffffffff81031039: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030920)
Location: arch/x86/kernel/dumpstack.c:244
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81030920-ffffffff810309de: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102ebf0)
Location: arch/x86/kernel/dumpstack.c:246
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8102ebf0-ffffffff8102eca7: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030ac0)
Location: arch/x86/kernel/dumpstack.c:306
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81030ac0-ffffffff81030b9a: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81032335)
Location: arch/x86/kernel/dumpstack.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81032335-ffffffff81032403: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810335fa)
Location: arch/x86/kernel/dumpstack.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810335fa-ffffffff810336c8: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103542a)
Location: arch/x86/kernel/dumpstack.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8103542a-ffffffff81035503: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035c5a)
Location: arch/x86/kernel/dumpstack.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81035c5a-ffffffff81035d33: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037cc6)
Location: arch/x86/kernel/dumpstack.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81037cc6-ffffffff81037cf9: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd388b)
Location: arch/x86/kernel/dumpstack.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81bd388b-ffffffff81bd38be: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5cfd)
Location: arch/x86/kernel/dumpstack.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81bc5cfd-ffffffff81bc5d30: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c98a47)
Location: arch/x86/kernel/dumpstack.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81c98a47-ffffffff81c98a7a: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e47fdc)
Location: arch/x86/kernel/dumpstack.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81e47fdc-ffffffff81e48017: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051dda)
Location: arch/x86/kernel/dumpstack.c:428
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:die
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81051d20-ffffffff81051d96: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052b1a)
Location: arch/x86/kernel/dumpstack.c:431
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:die
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81052a60-ffffffff81052ad6: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059d3a)
Location: arch/x86/kernel/dumpstack.c:431
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:die
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81059c80-ffffffff81059cf6: __die (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff8000100949a0)
Location: arch/arm64/kernel/traps.c:151
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:die
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c030f3b4)
Location: arch/arm/kernel/traps.c:265
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:die
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002f368)
Location: arch/powerpc/kernel/traps.c:262
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:die
```
**Symbols:**

```
c00000000002f368-c00000000002f4c4: __die (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035dba)
Location: arch/x86/kernel/dumpstack.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81035dba-ffffffff81035e93: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102570a)
Location: arch/x86/kernel/dumpstack.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8102570a-ffffffff810257e3: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035c1a)
Location: arch/x86/kernel/dumpstack.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81035c1a-ffffffff81035cf3: __die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __die(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81036bfa)
Location: arch/x86/kernel/dumpstack.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81036bfa-ffffffff81036cd3: __die (STB_GLOBAL)
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
