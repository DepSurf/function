# Function: <code>cr4_read_shadow</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107ab46)
Location: arch/x86/include/asm/tlbflush.h:290
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d8f6)
Location: arch/x86/include/asm/tlbflush.h:335
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81084426)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810880a3)
Location: arch/x86/include/asm/tlbflush.h:325
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088d66)
Location: arch/x86/include/asm/tlbflush.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049e40)
Location: arch/x86/kernel/cpu/common.c:412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff81049e40-ffffffff81049e49: cr4_read_shadow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810492e0)
Location: arch/x86/kernel/cpu/common.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff810492e0-ffffffff810492e9: cr4_read_shadow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104abb0)
Location: arch/x86/kernel/cpu/common.c:413
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff8104abb0-ffffffff8104abb9: cr4_read_shadow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051b10)
Location: arch/x86/kernel/cpu/common.c:421
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff81051b10-ffffffff81051b19: cr4_read_shadow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d200)
Location: arch/x86/kernel/cpu/common.c:477
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff8105d200-ffffffff8105d20d: cr4_read_shadow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106b650)
Location: arch/x86/kernel/cpu/common.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff8106b650-ffffffff8106b65d: cr4_read_shadow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d000)
Location: arch/x86/kernel/cpu/common.c:466
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff8106d000-ffffffff8106d00d: cr4_read_shadow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int cr4_read_shadow();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810740f0)
Location: arch/x86/kernel/cpu/common.c:447
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:itlb_multihit_show_state
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
**Symbols:**

```
ffffffff810740f0-ffffffff810740fd: cr4_read_shadow (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087d66)
Location: arch/x86/include/asm/tlbflush.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810769d0)
Location: arch/x86/include/asm/tlbflush.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087d16)
Location: arch/x86/include/asm/tlbflush.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089f06)
Location: arch/x86/include/asm/tlbflush.h:341
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
