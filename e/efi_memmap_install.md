# Function: <code>efi_memmap_install</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82022648)
Location: drivers/firmware/efi/memmap.c:191
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82022648-ffffffff820226bb: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82105348)
Location: drivers/firmware/efi/memmap.c:191
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82105348-ffffffff821053c0: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8270ea11)
Location: drivers/firmware/efi/memmap.c:192
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff8270ea11-ffffffff8270ea89: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82738cd0)
Location: drivers/firmware/efi/memmap.c:192
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82738cd0-ffffffff82738d48: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828f2c8b)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff828f2c8b-ffffffff828f2d03: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8290e593)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff8290e593-ffffffff8290e60b: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82917f6e)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82917f6e-ffffffff82917fe6: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82d2a68d)
Location: drivers/firmware/efi/memmap.c:235
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82d2a68d-ffffffff82d2a6ac: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83018da7)
Location: drivers/firmware/efi/memmap.c:235
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff83018da7-ffffffff83018dc6: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff83223d9f)
Location: drivers/firmware/efi/memmap.c:235
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff83223d9f-ffffffff83223dbe: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff8330dba5)
Location: drivers/firmware/efi/memmap.c:235
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff8330dba5-ffffffff8330dbc4: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff834c7945)
Location: drivers/firmware/efi/memmap.c:235
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff834c7945-ffffffff834c7968: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff83ea15f0)
Location: arch/x86/platform/efi/memmap.c:93
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff83ea15f0-ffffffff83ea1634: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff836c5830)
Location: arch/x86/platform/efi/memmap.c:93
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff836c5830-ffffffff836c5874: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_memmap_install(struct efi_memory_map_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/memmap.c (ffffffff838f6430)
Location: arch/x86/platform/efi/memmap.c:93
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff838f6430-ffffffff838f6474: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffff8000114a6924)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
```
**Symbols:**

```
ffff8000114a6924-ffff8000114a69a4: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (c15a8d0c)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
```
**Symbols:**

```
c15a8d0c-c15a8d98: efi_memmap_install (STB_GLOBAL)
```
</details>
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
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828fd374)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff828fd374-ffffffff828fd3ec: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff828f4c10)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff828f4c10-ffffffff828f4c88: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff829125a3)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff829125a3-ffffffff8291261b: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efi_memmap_install(phys_addr_t addr, unsigned int nr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/memmap.c (ffffffff82918fd0)
Location: drivers/firmware/efi/memmap.c:195
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82918fd0-ffffffff82919048: efi_memmap_install (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct efi_memory_map_data *data</code>
</li>
<li>
<b>Param removed. </b>
<code>phys_addr_t addr</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_map</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
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
