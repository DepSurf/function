# Function: <code>__early_make_pgtable</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826a32c9)
Location: arch/x86/kernel/head64.c:188
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff826a32c9-ffffffff826a34ae: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826cc2c6)
Location: arch/x86/kernel/head64.c:264
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff826cc2c6-ffffffff826cc48f: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff828822d1)
Location: arch/x86/kernel/head64.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff828822d1-ffffffff8288249a: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289926e)
Location: arch/x86/kernel/head64.c:282
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8289926e-ffffffff82899426: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289c26e)
Location: arch/x86/kernel/head64.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8289c26e-ffffffff8289c426: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82cc226e)
Location: arch/x86/kernel/head64.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff82cc226e-ffffffff82cc24e5: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82fae2ae)
Location: arch/x86/kernel/head64.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff82fae2ae-ffffffff82fae523: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff831b82ae)
Location: arch/x86/kernel/head64.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff831b82ae-ffffffff831b8523: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff832982ae)
Location: arch/x86/kernel/head64.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff832982ae-ffffffff8329859d: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff834462b0)
Location: arch/x86/kernel/head64.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
  - arch/x86/mm/mem_encrypt_amd.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff834462b0-ffffffff834465c4: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83e5f350)
Location: arch/x86/kernel/head64.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff83e5f350-ffffffff83e5f6ff: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83694580)
Location: arch/x86/kernel/head64.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff83694580-ffffffff83694948: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff838c4470)
Location: arch/x86/kernel/head64.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
  - arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata
```
**Symbols:**

```
ffffffff838c4470-ffffffff838c4838: __early_make_pgtable (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8288a26e)
Location: arch/x86/kernel/head64.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8288a26e-ffffffff8288a426: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82888216)
Location: arch/x86/kernel/head64.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff82888216-ffffffff828883ca: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d26e)
Location: arch/x86/kernel/head64.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8289d26e-ffffffff8289d426: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __early_make_pgtable(long unsigned int address, pmdval_t pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d26e)
Location: arch/x86/kernel/head64.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
**Symbols:**

```
ffffffff8289d26e-ffffffff8289d426: __early_make_pgtable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
