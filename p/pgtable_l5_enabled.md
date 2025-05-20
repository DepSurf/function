# Function: <code>pgtable_l5_enabled</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810002b0)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff82cd3fe4)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff810003a0)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff82fbff71)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff8100039f)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff831ca681)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
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
In arch/x86/kernel/head64.c (ffffffff810003a3)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff832abac2)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4937)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/head64.c (ffffffff810003ef)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8345bb4e)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477361)
Location: arch/x86/include/asm/pgtable_64_types.h:31
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/head64.c (ffffffff8100041f)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff83e7c29c)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea088d)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/head64.c (ffffffff8100052f)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8369e999)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c49fd)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In arch/x86/kernel/head64.c (ffffffff8100053f)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:__early_make_pgtable
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff838ce751)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f55fd)
Location: arch/x86/include/asm/pgtable_64_types.h:32
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
