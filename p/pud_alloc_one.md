# Function: <code>pud_alloc_one</code>

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
In mm/memory.c (ffffffff811be9d5)
Location: arch/x86/include/asm/pgalloc.h:126
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa377c)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811da7e6)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf0c6)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811ea356)
Location: arch/x86/include/asm/pgalloc.h:130
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f53d6)
Location: arch/x86/include/asm/pgalloc.h:132
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120e296)
Location: arch/x86/include/asm/pgalloc.h:144
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff8122ec95)
Location: arch/x86/include/asm/pgalloc.h:144
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff81241725)
Location: arch/x86/include/asm/pgalloc.h:163
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff812540a5)
Location: arch/x86/include/asm/pgalloc.h:150
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff81262605)
Location: arch/x86/include/asm/pgalloc.h:150
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff81292505)
Location: arch/x86/include/asm/pgalloc.h:150
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
In mm/memory.c (ffffffff8129cdb5)
Location: include/asm-generic/pgalloc.h:160
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
In mm/memory.c (ffffffff812a2495)
Location: include/asm-generic/pgalloc.h:160
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
In mm/memory.c (ffffffff812e3805)
Location: include/asm-generic/pgalloc.h:160
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
In mm/memory.c (ffffffff81344ba5)
Location: include/asm-generic/pgalloc.h:169
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
In mm/memory.c (ffffffff813bcdc5)
Location: include/asm-generic/pgalloc.h:169
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
In mm/memory.c (ffffffff813f1af5)
Location: include/asm-generic/pgalloc.h:169
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
In mm/memory.c (ffffffff8141c7a5)
Location: include/asm-generic/pgalloc.h:187
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
In virt/kvm/arm/mmu.c (ffff8000100c9060)
Location: arch/arm64/include/asm/pgalloc.h:65
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In mm/memory.c (ffff8000102f9830)
Location: arch/arm64/include/asm/pgalloc.h:65
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
In mm/memory.c (c0000000003c3790)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:93
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125ac55)
Location: arch/x86/include/asm/pgalloc.h:150
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff8124d025)
Location: arch/x86/include/asm/pgalloc.h:150
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff812589f5)
Location: arch/x86/include/asm/pgalloc.h:150
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
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
In mm/memory.c (ffffffff812683f5)
Location: arch/x86/include/asm/pgalloc.h:150
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
</details>
</li>
</ul>

## Differences
