# Function: <code>init_new_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int init_new_context(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ldt.c (ffffffff81032eb0)
Location: arch/x86/kernel/ldt.c:106
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81032eb0-ffffffff81032f9f: init_new_context (STB_GLOBAL)
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
In kernel/fork.c (ffffffff8107f7c3)
Location: arch/x86/include/asm/mmu_context.h:107
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In kernel/fork.c (ffffffff81083e74)
Location: arch/x86/include/asm/mmu_context.h:108
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In kernel/fork.c (ffffffff81080dbd)
Location: arch/x86/include/asm/mmu_context.h:132
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In kernel/fork.c (ffffffff81087734)
Location: arch/x86/include/asm/mmu_context.h:185
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
In arch/x86/platform/efi/efi_64.c (ffffffff826f2165)
Location: arch/x86/include/asm/mmu_context.h:186
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108ac5a)
Location: arch/x86/include/asm/mmu_context.h:186
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
In arch/x86/platform/efi/efi_64.c (ffffffff828a9175)
Location: arch/x86/include/asm/mmu_context.h:185
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092c57)
Location: arch/x86/include/asm/mmu_context.h:185
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c195c)
Location: arch/x86/include/asm/mmu_context.h:186
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c4c)
Location: arch/x86/include/asm/mmu_context.h:186
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c7dd5)
Location: arch/x86/include/asm/mmu_context.h:186
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109d480)
Location: arch/x86/include/asm/mmu_context.h:186
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
In arch/x86/platform/efi/efi_64.c (ffffffff82ceac1b)
Location: arch/x86/include/asm/mmu_context.h:101
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a42e0)
Location: arch/x86/include/asm/mmu_context.h:101
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
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8466)
Location: arch/x86/include/asm/mmu_context.h:102
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109fefc)
Location: arch/x86/include/asm/mmu_context.h:102
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
In arch/x86/platform/efi/efi_64.c (ffffffff831e2e5c)
Location: arch/x86/include/asm/mmu_context.h:102
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0c0f)
Location: arch/x86/include/asm/mmu_context.h:102
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
In arch/x86/platform/efi/efi_64.c (ffffffff832c67ff)
Location: arch/x86/include/asm/mmu_context.h:102
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b2082)
Location: arch/x86/include/asm/mmu_context.h:102
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
In arch/x86/platform/efi/efi_64.c (ffffffff8347959d)
Location: arch/x86/include/asm/mmu_context.h:102
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810c89da)
Location: arch/x86/include/asm/mmu_context.h:102
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
In arch/x86/platform/efi/efi_64.c (ffffffff83ea36d8)
Location: arch/x86/include/asm/mmu_context.h:102
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810e5d37)
Location: arch/x86/include/asm/mmu_context.h:102
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
In arch/x86/platform/efi/efi_64.c (ffffffff836c7968)
Location: arch/x86/include/asm/mmu_context.h:141
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810f14b3)
Location: arch/x86/include/asm/mmu_context.h:141
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
In arch/x86/platform/efi/efi_64.c (ffffffff838f8568)
Location: arch/x86/include/asm/mmu_context.h:141
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810fa895)
Location: arch/x86/include/asm/mmu_context.h:141
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350b80)
Location: arch/arm/include/asm/mmu_context.h:30
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In drivers/firmware/efi/arm-runtime.c (c15aa044)
Location: arch/arm/include/asm/mmu_context.h:30
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int init_new_context(struct task_struct *tsk, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/mmu_context.c (c0000000000901f0)
Location: arch/powerpc/mm/book3s64/mmu_context.c:182
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
c0000000000901f0-c0000000000904c4: init_new_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (0)
Location: arch/riscv/include/asm/mmu_context.h:22
Inline: True
```
</details>
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
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d6d)
Location: arch/x86/include/asm/mmu_context.h:186
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096da0)
Location: arch/x86/include/asm/mmu_context.h:186
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
In arch/x86/platform/efi/efi_64.c (ffffffff828aaeee)
Location: arch/x86/include/asm/mmu_context.h:186
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81085820)
Location: arch/x86/include/asm/mmu_context.h:186
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c6c)
Location: arch/x86/include/asm/mmu_context.h:186
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096d50)
Location: arch/x86/include/asm/mmu_context.h:186
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
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e12)
Location: arch/x86/include/asm/mmu_context.h:186
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ebf0)
Location: arch/x86/include/asm/mmu_context.h:186
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
</ul>
<b>Arch</b>
<ul>
</ul>
