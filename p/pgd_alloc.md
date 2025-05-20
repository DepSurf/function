# Function: <code>pgd_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070d90)
Location: arch/x86/mm/pgtable.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81070d90-ffffffff81070ea0: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070ca0)
Location: arch/x86/mm/pgtable.c:358
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81070ca0-ffffffff81070dd1: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074830)
Location: arch/x86/mm/pgtable.c:358
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81074830-ffffffff8107495b: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81073d80)
Location: arch/x86/mm/pgtable.c:368
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81073d80-ffffffff81073eab: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079770)
Location: arch/x86/mm/pgtable.c:370
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81079770-ffffffff810798d9: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c340)
Location: arch/x86/mm/pgtable.c:375
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff8107c340-ffffffff8107c4af: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81082cc0)
Location: arch/x86/mm/pgtable.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81082cc0-ffffffff81082e9b: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810868f0)
Location: arch/x86/mm/pgtable.c:421
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff810868f0-ffffffff81086af1: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810875e0)
Location: arch/x86/mm/pgtable.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff810875e0-ffffffff810877e1: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089b20)
Location: arch/x86/mm/pgtable.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_create_trampoline
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81089b20-ffffffff81089bf6: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089da0)
Location: arch/x86/mm/pgtable.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_create_trampoline
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81089da0-ffffffff81089e76: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a9f0)
Location: arch/x86/mm/pgtable.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff8108a9f0-ffffffff8108aadb: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81ca1109-ffffffff81ca1140: pgd_alloc.cold (STB_LOCAL)
ffffffff81099f70-ffffffff8109a07e: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/mm/pgtable.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81e5070a-ffffffff81e50741: pgd_alloc.cold (STB_LOCAL)
ffffffff810ad020-ffffffff810ad13c: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c7110)
Location: arch/x86/mm/pgtable.c:421
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff810c7110-ffffffff810c71c4: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ca860)
Location: arch/x86/mm/pgtable.c:421
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff810ca860-ffffffff810ca917: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d2db0)
Location: arch/x86/mm/pgtable.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff810d2db0-ffffffff810d2e67: pgd_alloc (STB_GLOBAL)
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
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pgd.c (ffff8000100ae148)
Location: arch/arm64/mm/pgd.c:20
Inline: False
Direct callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:mm_init
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
**Symbols:**

```
ffff8000100ae148-ffff8000100ae170: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/pgd.c (c031f7d4)
Location: arch/arm/mm/pgd.c:30
Inline: False
Direct callers:
  - arch/arm/mm/idmap.c:init_static_idmap
  - kernel/fork.c:mm_init
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
**Symbols:**

```
c031f7d4-c031f92c: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0000000001373c0)
Location: arch/powerpc/include/asm/book3s/64/pgalloc.h:48
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
In kernel/fork.c (ffffffe0000bec80)
Location: arch/riscv/include/asm/pgalloc.h:42
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
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
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810865e0)
Location: arch/x86/mm/pgtable.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff810865e0-ffffffff810867e1: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81075300)
Location: arch/x86/mm/pgtable.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81075300-ffffffff810754d1: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086590)
Location: arch/x86/mm/pgtable.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff81086590-ffffffff81086791: pgd_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pgd_t *pgd_alloc(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810886d0)
Location: arch/x86/mm/pgtable.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
  - kernel/fork.c:mm_init
```
**Symbols:**

```
ffffffff810886d0-ffffffff810888cf: pgd_alloc (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
