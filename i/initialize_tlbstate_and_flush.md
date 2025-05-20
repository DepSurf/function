# Function: <code>initialize_tlbstate_and_flush</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107aad0)
Location: arch/x86/mm/tlb.c:380
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8107aad0-ffffffff8107abf1: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d880)
Location: arch/x86/mm/tlb.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8107d880-ffffffff8107d9a6: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810843b0)
Location: arch/x86/mm/tlb.c:481
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff810843b0-ffffffff810844dd: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81088513-ffffffff81088539: initialize_tlbstate_and_flush.cold (STB_LOCAL)
ffffffff81088030-ffffffff810881b0: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088cf0)
Location: arch/x86/mm/tlb.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81088cf0-ffffffff81088e1d: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b350)
Location: arch/x86/mm/tlb.c:658
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8108b350-ffffffff8108b4f1: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b410)
Location: arch/x86/mm/tlb.c:617
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8108b410-ffffffff8108b5b1: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bfa0)
Location: arch/x86/mm/tlb.c:624
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8108bfa0-ffffffff8108c141: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109b760)
Location: arch/x86/mm/tlb.c:683
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8109b760-ffffffff8109b901: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810aec50)
Location: arch/x86/mm/tlb.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff810aec50-ffffffff810aedf0: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8fc0)
Location: arch/x86/mm/tlb.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff810c8fc0-ffffffff810c9160: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cc600)
Location: arch/x86/mm/tlb.c:698
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff810cc600-ffffffff810cc7e2: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d4c90)
Location: arch/x86/mm/tlb.c:699
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff810d4c90-ffffffff810d4e72: initialize_tlbstate_and_flush (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087cf0)
Location: arch/x86/mm/tlb.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81087cf0-ffffffff81087e1d: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076960)
Location: arch/x86/mm/tlb.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81076960-ffffffff81076a7e: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087ca0)
Location: arch/x86/mm/tlb.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81087ca0-ffffffff81087dcd: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void initialize_tlbstate_and_flush();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089e90)
Location: arch/x86/mm/tlb.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81089e90-ffffffff81089fbd: initialize_tlbstate_and_flush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
