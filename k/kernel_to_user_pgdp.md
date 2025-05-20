# Function: <code>kernel_to_user_pgdp</code>

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
In arch/x86/kernel/ldt.c (ffffffff81031eb4)
Location: arch/x86/include/asm/pgtable_64.h:163
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81079824)
Location: arch/x86/include/asm/pgtable_64.h:163
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107cb1a)
Location: arch/x86/include/asm/pgtable_64.h:163
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff826c592b)
Location: arch/x86/include/asm/pgtable_64.h:163
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgd
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
In arch/x86/kernel/ldt.c (ffffffff81033161)
Location: arch/x86/include/asm/pgtable_64.h:164
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c3f4)
Location: arch/x86/include/asm/pgtable_64.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107faec)
Location: arch/x86/include/asm/pgtable_64.h:164
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff826efa16)
Location: arch/x86/include/asm/pgtable_64.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgd
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
In arch/x86/kernel/ldt.c (ffffffff810343a0)
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81082db7)
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108662b)
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff828a66cd)
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81036124)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810869ef)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a233)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff828beccc)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81036a4b)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810876df)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108aeaf)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff828c51a3)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81038567)
Location: arch/x86/include/asm/pgtable.h:1227
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff810897c3)
Location: arch/x86/include/asm/pgtable.h:1227
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8109224f)
Location: arch/x86/include/asm/pgtable.h:1227
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff82ce8239)
Location: arch/x86/include/asm/pgtable.h:1227
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_setup_vsyscall
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81038f17)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff810899a3)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81bd9ed4)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff82fd5c58)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_setup_vsyscall
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff8103aa0e)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff8108aa7f)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81bcbf43)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff831e08b5)
Location: arch/x86/include/asm/pgtable.h:1223
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81040409)
Location: arch/x86/include/asm/pgtable.h:1194
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a00c)
Location: arch/x86/include/asm/pgtable.h:1194
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81ca1d65)
Location: arch/x86/include/asm/pgtable.h:1194
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff832c3f93)
Location: arch/x86/include/asm/pgtable.h:1194
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff810480df)
Location: arch/x86/include/asm/pgtable.h:1211
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad0b6)
Location: arch/x86/include/asm/pgtable.h:1211
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81e513b5)
Location: arch/x86/include/asm/pgtable.h:1211
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff834768ae)
Location: arch/x86/include/asm/pgtable.h:1211
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81052e1f)
Location: arch/x86/include/asm/pgtable.h:1229
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff810c6cad)
Location: arch/x86/include/asm/pgtable.h:1229
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810d185f)
Location: arch/x86/include/asm/pgtable.h:1229
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff83e9f8f4)
Location: arch/x86/include/asm/pgtable.h:1229
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81053e02)
Location: arch/x86/include/asm/pgtable.h:1230
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff810ca425)
Location: arch/x86/include/asm/pgtable.h:1230
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810d4d0f)
Location: arch/x86/include/asm/pgtable.h:1230
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff836c3a84)
Location: arch/x86/include/asm/pgtable.h:1230
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff8105b022)
Location: arch/x86/include/asm/pgtable.h:1453
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/mm/pgtable.c (ffffffff810d2915)
Location: arch/x86/include/asm/pgtable.h:1453
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810dd4af)
Location: arch/x86/include/asm/pgtable.h:1453
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff838f4674)
Location: arch/x86/include/asm/pgtable.h:1453
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff81036bab)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810866df)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089e6f)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff828b013b)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff810264db)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810753ed)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81078a4f)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff828a8328)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
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
In arch/x86/kernel/ldt.c (ffffffff81036a0b)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108668f)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089e1f)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff828c303a)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
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
In arch/x86/kernel/ldt.c (ffffffff8103790b)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810887cf)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108c0bf)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/pti.c (ffffffff828c61c3)
Location: arch/x86/include/asm/pgtable.h:1266
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:__pti_set_user_pgtbl
```
</details>
</li>
</ul>

## Differences
