# Function: <code>init_new_context_ldt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_new_context_ldt(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032040)
Location: arch/x86/kernel/ldt.c:106
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81032040-ffffffff81032134: init_new_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_new_context_ldt(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81031cc0)
Location: arch/x86/kernel/ldt.c:106
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81031cc0-ffffffff81031db1: init_new_context_ldt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_new_context_ldt(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff8102fed0)
Location: arch/x86/kernel/ldt.c:107
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff8102fed0-ffffffff8102ffc2: init_new_context_ldt (STB_GLOBAL)
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
In kernel/fork.c (ffffffff81087781)
Location: arch/x86/include/asm/mmu_context.h:84
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff826f21a3)
Location: arch/x86/include/asm/mmu_context.h:85
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108aca7)
Location: arch/x86/include/asm/mmu_context.h:85
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff828a91b3)
Location: arch/x86/include/asm/mmu_context.h:80
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092ca4)
Location: arch/x86/include/asm/mmu_context.h:80
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c199a)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c9e)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c7e13)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109d4d2)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff82ceac59)
Location: arch/x86/include/asm/mmu_context.h:62
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a4332)
Location: arch/x86/include/asm/mmu_context.h:62
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd84a4)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ff4e)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e9a)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0c61)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff832c683d)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b20d4)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff834795d9)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c8a27)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3725)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5d84)
Location: arch/x86/include/asm/mmu_context.h:61
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff836c79d5)
Location: arch/x86/include/asm/mmu_context.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f151a)
Location: arch/x86/include/asm/mmu_context.h:55
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff838f85d5)
Location: arch/x86/include/asm/mmu_context.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa8fc)
Location: arch/x86/include/asm/mmu_context.h:55
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff828b2dab)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096df2)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff828aaf2c)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81085872)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c5caa)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096da2)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e50)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ec42)
Location: arch/x86/include/asm/mmu_context.h:81
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
