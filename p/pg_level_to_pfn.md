# Function: <code>pg_level_to_pfn</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t *kpte, pgprot_t *ret_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:251
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
**Symbols:**

```
ffffffff810b9790-ffffffff810b98db: pg_level_to_pfn (STB_LOCAL)
ffffffff81e51cda-ffffffff81e51cee: pg_level_to_pfn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t *kpte, pgprot_t *ret_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:252
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
**Symbols:**

```
ffffffff810d5410-ffffffff810d5574: pg_level_to_pfn (STB_LOCAL)
ffffffff8205540b-ffffffff8205541f: pg_level_to_pfn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t *kpte, pgprot_t *ret_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:252
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
**Symbols:**

```
ffffffff810d8970-ffffffff810d8acd: pg_level_to_pfn (STB_LOCAL)
ffffffff820d39d6-ffffffff820d39ea: pg_level_to_pfn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int pg_level_to_pfn(int level, pte_t *kpte, pgprot_t *ret_prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/mm/mem_encrypt_amd.c:217
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
**Symbols:**

```
ffffffff810e11f0-ffffffff810e134d: pg_level_to_pfn (STB_LOCAL)
ffffffff821ae844-ffffffff821ae858: pg_level_to_pfn.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
