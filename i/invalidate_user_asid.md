# Function: <code>invalidate_user_asid</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106b251)
Location: arch/x86/include/asm/tlbflush.h:328
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8107a2b3)
Location: arch/x86/include/asm/tlbflush.h:328
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c599d)
Location: arch/x86/include/asm/tlbflush.h:328
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106debe)
Location: arch/x86/include/asm/tlbflush.h:373
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff8107d057)
Location: arch/x86/include/asm/tlbflush.h:373
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa73)
Location: arch/x86/include/asm/tlbflush.h:373
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073e4e)
Location: arch/x86/include/asm/tlbflush.h:361
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81083a97)
Location: arch/x86/include/asm/tlbflush.h:361
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6730)
Location: arch/x86/include/asm/tlbflush.h:361
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810779ee)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087741)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedcc)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078a5e)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81088431)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5245)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b9f1)
Location: arch/x86/mm/tlb.c:249
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ba41)
Location: arch/x86/mm/tlb.c:248
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void invalidate_user_asid(u16 asid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b6e0)
Location: arch/x86/mm/tlb.c:249
Inline: True
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
**Symbols:**

```
ffffffff8108b6e0-ffffffff8108b70b: invalidate_user_asid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void invalidate_user_asid(u16 asid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109acc0)
Location: arch/x86/mm/tlb.c:256
Inline: True
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
**Symbols:**

```
ffffffff8109acc0-ffffffff8109aceb: invalidate_user_asid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void invalidate_user_asid(u16 asid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae050)
Location: arch/x86/mm/tlb.c:257
Inline: True
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
**Symbols:**

```
ffffffff810ae050-ffffffff810ae07c: invalidate_user_asid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void invalidate_user_asid(u16 asid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c82e0)
Location: arch/x86/mm/tlb.c:257
Inline: True
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
**Symbols:**

```
ffffffff810c82e0-ffffffff810c830c: invalidate_user_asid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void invalidate_user_asid(u16 asid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cba20)
Location: arch/x86/mm/tlb.c:261
Inline: True
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810cba20-ffffffff810cba4c: invalidate_user_asid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void invalidate_user_asid(u16 asid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d40b0)
Location: arch/x86/mm/tlb.c:262
Inline: True
Direct callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810d40b0-ffffffff810d40dc: invalidate_user_asid (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077a5e)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81087431)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b01dd)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106773e)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81075ff7)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83ca)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077a0e)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff810873e1)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c30dc)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079aae)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/tlb.c (ffffffff81089511)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6282)
Location: arch/x86/include/asm/tlbflush.h:379
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
