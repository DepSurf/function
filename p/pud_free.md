# Function: <code>pud_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bea7f)
Location: arch/x86/include/asm/pgalloc.h:131
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811da8a9)
Location: arch/x86/include/asm/pgalloc.h:139
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ea419)
Location: arch/x86/include/asm/pgalloc.h:139
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff820bff18)
Location: arch/x86/include/asm/pgalloc.h:141
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff811f549a)
Location: arch/x86/include/asm/pgalloc.h:141
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff826c80ac)
Location: arch/x86/include/asm/pgalloc.h:153
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8120e358)
Location: arch/x86/include/asm/pgalloc.h:153
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In arch/x86/platform/efi/efi_64.c (ffffffff826f267b)
Location: arch/x86/include/asm/pgalloc.h:153
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8122ed5b)
Location: arch/x86/include/asm/pgalloc.h:153
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In arch/x86/platform/efi/efi_64.c (ffffffff828a8f87)
Location: arch/x86/include/asm/pgalloc.h:172
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff812417eb)
Location: arch/x86/include/asm/pgalloc.h:172
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c15b4)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81254165)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c7a33)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff812626c5)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec22a)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
```
```
In mm/memory.c (ffffffff812925c5)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff8129ce75)
Location: include/asm-generic/pgalloc.h:170
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2556)
Location: include/asm-generic/pgalloc.h:170
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e38c6)
Location: include/asm-generic/pgalloc.h:170
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81344c65)
Location: include/asm-generic/pgalloc.h:182
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bce85)
Location: include/asm-generic/pgalloc.h:182
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f1bbb)
Location: include/asm-generic/pgalloc.h:182
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141c832)
Location: include/asm-generic/pgalloc.h:203
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/mmu.c (ffff8000100c96f0)
Location: arch/arm64/include/asm/pgalloc.h:70
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
```
```
In mm/memory.c (ffff8000102f9910)
Location: arch/arm64/include/asm/pgalloc.h:70
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c3890)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:110
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828b29cb)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8125ad15)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In arch/x86/platform/efi/efi_64.c (ffffffff828aab5f)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8124d06c)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c58ca)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81258ab5)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c8a70)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff812684b5)
Location: arch/x86/include/asm/pgalloc.h:159
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
</ul>

## Differences
