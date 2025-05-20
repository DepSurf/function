# Function: <code>kernel_map_pages_in_pgd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f530)
Location: arch/x86/mm/pageattr.c:1945
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff8106f530-ffffffff8106f5ec: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f270)
Location: arch/x86/mm/pageattr.c:1953
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff8106f270-ffffffff8106f333: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072ee0)
Location: arch/x86/mm/pageattr.c:1953
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff81072ee0-ffffffff81072fac: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072450)
Location: arch/x86/mm/pageattr.c:1999
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff81072450-ffffffff8107251a: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077cc0)
Location: arch/x86/mm/pageattr.c:2063
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff81077cc0-ffffffff81077d9a: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a790)
Location: arch/x86/mm/pageattr.c:2114
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff8107a790-ffffffff8107a868: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828a4750)
Location: arch/x86/mm/pageattr.c:2302
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff828a4750-ffffffff828a483e: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828bcc21)
Location: arch/x86/mm/pageattr.c:2317
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff828bcc21-ffffffff828bcd11: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828c30bc)
Location: arch/x86/mm/pageattr.c:2207
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff828c30bc-ffffffff828c31a5: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff82ce68a5)
Location: arch/x86/mm/pat/set_memory.c:2243
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff82ce68a5-ffffffff82ce698e: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff82fd41eb)
Location: arch/x86/mm/pat/set_memory.c:2243
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:sev_es_efi_map_ghcbs
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff82fd41eb-ffffffff82fd42d4: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff831decf4)
Location: arch/x86/mm/pat/set_memory.c:2251
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff831decf4-ffffffff831deddd: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff832c21ca)
Location: arch/x86/mm/pat/set_memory.c:2251
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff832c21ca-ffffffff832c22cd: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff834748ae)
Location: arch/x86/mm/pat/set_memory.c:2302
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff834748ae-ffffffff834749cd: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff83e9c980)
Location: arch/x86/mm/pat/set_memory.c:2406
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff83e9c980-ffffffff83e9cabb: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff836c04a0)
Location: arch/x86/mm/pat/set_memory.c:2405
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff836c04a0-ffffffff836c05db: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff838f0fc0)
Location: arch/x86/mm/pat/set_memory.c:2409
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff838f0fc0-ffffffff838f10fb: kernel_map_pages_in_pgd (STB_GLOBAL)
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
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828ae092)
Location: arch/x86/mm/pageattr.c:2207
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff828ae092-ffffffff828ae17b: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828a6284)
Location: arch/x86/mm/pageattr.c:2207
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff828a6284-ffffffff828a636d: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828c0f91)
Location: arch/x86/mm/pageattr.c:2207
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff828c0f91-ffffffff828c107a: kernel_map_pages_in_pgd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_map_pages_in_pgd(pgd_t *pgd, u64 pfn, long unsigned int address, unsigned int numpages, long unsigned int page_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff828c40dc)
Location: arch/x86/mm/pageattr.c:2207
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_update_mappings
  - arch/x86/platform/efi/efi_64.c:__map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
```
**Symbols:**

```
ffffffff828c40dc-ffffffff828c41c5: kernel_map_pages_in_pgd (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
