# Function: <code>early_snp_set_memory_shared</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff834714ee)
Location: arch/x86/kernel/sev.c:723
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/sev.c:snp_prep_memory
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:snp_memcpy
```
**Symbols:**

```
ffffffff834714ee-ffffffff83471535: early_snp_set_memory_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e986bd)
Location: arch/x86/kernel/sev.c:723
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_prep_memory
Direct callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:snp_memcpy
```
**Symbols:**

```
ffffffff83e98610-ffffffff83e98657: early_snp_set_memory_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bc0f1)
Location: arch/x86/kernel/sev.c:734
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_prep_memory
Direct callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:snp_memcpy
```
**Symbols:**

```
ffffffff836bc060-ffffffff836bc092: early_snp_set_memory_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void early_snp_set_memory_shared(long unsigned int vaddr, long unsigned int paddr, long unsigned int npages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838ecad1)
Location: arch/x86/kernel/sev.c:761
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:snp_prep_memory
Direct callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:snp_memcpy
```
**Symbols:**

```
ffffffff838eca40-ffffffff838eca72: early_snp_set_memory_shared (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int npages</code> ➡️ <code>long unsigned int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
