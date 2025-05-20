# Function: <code>mmap_is_ia32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81033f83)
Location: arch/x86/include/asm/elf.h:345
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff8106f666)
Location: arch/x86/include/asm/elf.h:345
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
  - arch/x86/mm/mmap.c:arch_pick_mmap_layout
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81033153)
Location: arch/x86/include/asm/elf.h:345
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff8106f396)
Location: arch/x86/include/asm/elf.h:345
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81032dd3)
Location: arch/x86/include/asm/elf.h:354
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81072ff6)
Location: arch/x86/include/asm/elf.h:354
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81030f75)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff8107267c)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In fs/binfmt_elf.c (ffffffff812b5361)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812b8012)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81033187)
Location: arch/x86/include/asm/elf.h:302
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81077efc)
Location: arch/x86/include/asm/elf.h:302
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In fs/binfmt_elf.c (ffffffff812d8c0c)
Location: arch/x86/include/asm/elf.h:302
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812db936)
Location: arch/x86/include/asm/elf.h:302
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81034541)
Location: arch/x86/include/asm/elf.h:302
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff8107a965)
Location: arch/x86/include/asm/elf.h:302
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In fs/binfmt_elf.c (ffffffff81304abc)
Location: arch/x86/include/asm/elf.h:302
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813084e4)
Location: arch/x86/include/asm/elf.h:302
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81035721)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff810812a5)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In fs/binfmt_elf.c (ffffffff8131a21b)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8131dcf4)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810378a6)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81084f05)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In fs/binfmt_elf.c (ffffffff81341752)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813451cf)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81038076)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81085bf5)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff812456bc)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff81359bb1)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8103a9d6)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff81089335)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff812733ec)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff813a1313)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813a40cf)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8103b1e6)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff81089515)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff8127db4c)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff813b2619)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813b4e0c)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8103cbb6)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff8108a225)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff81282d1c)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff813b970f)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813bbe2b)
Location: arch/x86/include/asm/elf.h:320
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810426b6)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff81099765)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff812c0e0c)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff8140941f)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8140bb2b)
Location: arch/x86/include/asm/elf.h:321
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8104a89f)
Location: arch/x86/include/asm/elf.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff810ac645)
Location: arch/x86/include/asm/elf.h:310
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff8131dbe7)
Location: arch/x86/include/asm/elf.h:310
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff8147e07d)
Location: arch/x86/include/asm/elf.h:310
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81480ab6)
Location: arch/x86/include/asm/elf.h:310
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int mmap_is_ia32();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81056156)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff810c66a5)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff813916c7)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff81510e04)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81513a69)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81510150-ffffffff81510168: mmap_is_ia32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int mmap_is_ia32();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_x86_64.c (ffffffff81057126)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff810c9e35)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff813c4097)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff81548749)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8154b4c9)
Location: arch/x86/include/asm/elf.h:305
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81547a80-ffffffff81547a98: mmap_is_ia32 (STB_LOCAL)
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
In arch/x86/kernel/sys_x86_64.c (ffffffff8105e376)
Location: arch/x86/include/asm/elf.h:306
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
  - arch/x86/kernel/sys_x86_64.c:align_vdso_addr
```
```
In arch/x86/mm/mmap.c (ffffffff810d2295)
Location: arch/x86/include/asm/elf.h:306
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff813eec47)
Location: arch/x86/include/asm/elf.h:306
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff8157dbd5)
Location: arch/x86/include/asm/elf.h:306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81580955)
Location: arch/x86/include/asm/elf.h:306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff810381d6)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81084bf5)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff8123dd0c)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff81352191)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81027bb6)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff810738c5)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff81230d0c)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff81342e71)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81038036)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81084ba5)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff8123baac)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff8134fc61)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
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
In arch/x86/kernel/sys_x86_64.c (ffffffff81039036)
Location: arch/x86/include/asm/elf.h:301
Inline: True
```
```
In arch/x86/mm/mmap.c (ffffffff81086cf5)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:arch_mmap_rnd
```
```
In mm/util.c (ffffffff8124b1bc)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - mm/util.c:randomize_stack_top
```
```
In fs/binfmt_elf.c (ffffffff813631e1)
Location: arch/x86/include/asm/elf.h:301
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
