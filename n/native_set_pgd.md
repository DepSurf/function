# Function: <code>native_set_pgd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064680)
Location: arch/x86/include/asm/pgtable_64.h:109
Inline: False
```
**Symbols:**

```
ffffffff81064680-ffffffff81064689: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810642d0)
Location: arch/x86/include/asm/pgtable_64.h:109
Inline: False
```
**Symbols:**

```
ffffffff810642d0-ffffffff810642d9: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810677a0)
Location: arch/x86/include/asm/pgtable_64.h:109
Inline: False
```
**Symbols:**

```
ffffffff810677a0-ffffffff810677a9: native_set_pgd (STB_LOCAL)
```
</details>
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
In arch/x86/mm/mem_encrypt.c (ffffffff826c5ac1)
Location: arch/x86/include/asm/pgtable_64.h:237
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_prepare_pgd
```
</details>
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
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107ff30)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c12)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8107ff30-ffffffff8107ff51: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fb50)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6698)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8107fb50-ffffffff8107fb71: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080c70)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e10ec)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff81080c70-ffffffff81080c91: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108fbe0)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c496f)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff8108fbe0-ffffffff8108fc01: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a0a20)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477399)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810a0a20-ffffffff810a0a4b: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b8720)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0998)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810b8720-ffffffff810b8748: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb8f0)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4b57)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810bb8f0-ffffffff810bb918: native_set_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810c2d00)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5757)
Location: arch/x86/include/asm/pgtable_64.h:161
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
**Symbols:**

```
ffffffff810c2d00-ffffffff810c2d28: native_set_pgd (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
