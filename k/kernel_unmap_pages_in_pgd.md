# Function: <code>kernel_unmap_pages_in_pgd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kernel_unmap_pages_in_pgd(pgd_t *root, long unsigned int address, unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f5f0)
Location: arch/x86/mm/pageattr.c:1975
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_cleanup_page_tables
```
**Symbols:**

```
ffffffff8106f5f0-ffffffff8106f606: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828a483e)
Location: arch/x86/mm/pageattr.c:2345
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff828a483e-ffffffff828a48dc: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828bcd11)
Location: arch/x86/mm/pageattr.c:2360
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff828bcd11-ffffffff828bcdb3: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828c31a5)
Location: arch/x86/mm/pageattr.c:2244
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff828c31a5-ffffffff828c3248: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff82ce698e)
Location: arch/x86/mm/pat/set_memory.c:2280
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff82ce698e-ffffffff82ce6a31: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff82fd42d4)
Location: arch/x86/mm/pat/set_memory.c:2280
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff82fd42d4-ffffffff82fd4377: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff831deddd)
Location: arch/x86/mm/pat/set_memory.c:2288
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff831deddd-ffffffff831dee80: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff832c22cd)
Location: arch/x86/mm/pat/set_memory.c:2288
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff832c22cd-ffffffff832c238a: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff834749cd)
Location: arch/x86/mm/pat/set_memory.c:2339
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff834749cd-ffffffff83474a91: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff83e9cad0)
Location: arch/x86/mm/pat/set_memory.c:2443
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff83e9cad0-ffffffff83e9cba3: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff836c05f0)
Location: arch/x86/mm/pat/set_memory.c:2442
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff836c05f0-ffffffff836c06c3: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff838f1110)
Location: arch/x86/mm/pat/set_memory.c:2446
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff838f1110-ffffffff838f11e3: kernel_unmap_pages_in_pgd (STB_GLOBAL)
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
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828ae17b)
Location: arch/x86/mm/pageattr.c:2244
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff828ae17b-ffffffff828ae21e: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828a636d)
Location: arch/x86/mm/pageattr.c:2244
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff828a636d-ffffffff828a6410: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828c107a)
Location: arch/x86/mm/pageattr.c:2244
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff828c107a-ffffffff828c111d: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_unmap_pages_in_pgd(pgd_t *pgd, long unsigned int address, long unsigned int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828c41c5)
Location: arch/x86/mm/pageattr.c:2244
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff828c41c5-ffffffff828c4268: kernel_unmap_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
