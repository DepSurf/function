# Function: <code>native_set_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f62349)
Location: arch/x86/include/asm/pgtable_64.h:53
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064650)
Location: arch/x86/include/asm/pgtable_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
**Symbols:**

```
ffffffff81064650-ffffffff81064659: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81f89e9d)
Location: arch/x86/include/asm/pgtable_64.h:53
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810642e1)
Location: arch/x86/include/asm/pgtable_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
**Symbols:**

```
ffffffff810642a0-ffffffff810642a9: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81fc5297)
Location: arch/x86/include/asm/pgtable_64.h:53
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810677b1)
Location: arch/x86/include/asm/pgtable_64.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
**Symbols:**

```
ffffffff81067770-ffffffff81067779: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff820a60d9)
Location: arch/x86/include/asm/pgtable_64.h:62
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066a71)
Location: arch/x86/include/asm/pgtable_64.h:62
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
**Symbols:**

```
ffffffff81066a30-ffffffff81066a39: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826ac7a3)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ac21)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5bc3)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_populate_pgd
```
**Symbols:**

```
ffffffff8106abf0-ffffffff8106abf9: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d8e0)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f02ab)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
**Symbols:**

```
ffffffff8106d8b0-ffffffff8106d8b4: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073a80)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6fbb)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff8123f28f)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff8125abfd)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff81073a50-ffffffff81073a54: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810775e0)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf671)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff81250bcf)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff81275a8f)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
**Symbols:**

```
ffffffff810775b0-ffffffff810775b4: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078650)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5af0)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff8125f1a9)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff81284a5f)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff81078620-ffffffff81078624: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fa50)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8d90)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff8128f583)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812b6c4b)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff8107fa20-ffffffff8107fa24: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107f650)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6816)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff8129a08e)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e19)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff8107f650-ffffffff8107f654: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080750)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e127c)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff8129f2b2)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c9c92)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff81080750-ffffffff81080754: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108f670)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4b06)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff812e0518)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8130ecb2)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff8108f670-ffffffff8108f674: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff834527eb)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a03f0)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477538)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff81340b97)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81376f7f)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff810a03f0-ffffffff810a03fc: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f83b)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b7f50)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0b74)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff813b8b3c)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff813f4415)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff810b7f50-ffffffff810b7f5c: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff836909cb)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb100)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4c7f)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff813ed776)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81427bf1)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff810bb100-ffffffff810bb10c: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff838c049b)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2550)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: False
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f587f)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/memory.c (ffffffff81418d48)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81461407)
Location: arch/x86/include/asm/pgtable_64.h:65
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff810c2550-ffffffff810c255c: native_set_pte (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077650)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0a88)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff812577f9)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff8127d0af)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff81077620-ffffffff81077624: native_set_pte (STB_LOCAL)
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
In arch/x86/kernel/ldt.c (ffffffff8102695f)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810283da)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81029a63)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/kernel/tboot.c (ffffffff82894a98)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ef76)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a27240)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:__set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_init
  - arch/x86/mm/init_64.c:set_pte_init
```
```
In arch/x86/mm/ioremap.c (ffffffff828a61c1)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/pageattr.c (ffffffff8107241a)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81075a04)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pud_set_huge
  - arch/x86/mm/pgtable.c:ptep_set_access_flags
```
```
In arch/x86/mm/kmmio.c (ffffffff81078c83)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8692)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8c0d)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In kernel/events/uprobes.c (ffffffff81205617)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/shmem.c (ffffffff8122b53f)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffff8124564c)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124da9a)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff81258de6)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a341)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125ee63)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff81260977)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff8126ee08)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff8127505c)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81280807)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a505)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
```
In mm/ksm.c (ffffffff812896f4)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81298a74)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129e0e3)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a68f3)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812bc5b6)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8133088d)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135a1eb)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81865423)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0bca3)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077600)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3987)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff81255599)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff8127ae4f)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff810775d0-ffffffff810775d4: native_set_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_set_pte(pte_t *ptep, pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810796a0)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pte_at
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6b2d)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/memory.c (ffffffff81265048)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa28)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
**Symbols:**

```
ffffffff81079670-ffffffff81079674: native_set_pte (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
