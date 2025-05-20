# Function: <code>efi_mem_desc_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81fb676b)
Location: drivers/firmware/efi/efi.c:254
Inline: False
Direct callers:
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81fb676b-ffffffff81fb69d2: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81fe3f60)
Location: drivers/firmware/efi/efi.c:354
Inline: False
Direct callers:
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81fe3f60-ffffffff81fe4196: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82021d2f)
Location: drivers/firmware/efi/efi.c:361
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82021d2f-ffffffff82021e2b: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82104a41)
Location: drivers/firmware/efi/efi.c:361
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff82104a41-ffffffff82104b23: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8270e0f0)
Location: drivers/firmware/efi/efi.c:381
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8270e0f0-ffffffff8270e1d2: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8273837b)
Location: drivers/firmware/efi/efi.c:392
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8273837b-ffffffff8273844c: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:408
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff81871292-ffffffff818712cc: efi_mem_desc_lookup.cold.9 (STB_LOCAL)
ffffffff81870fc0-ffffffff818710b3: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:408
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff818b5508-ffffffff818b5542: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff818b52a0-ffffffff818b535b: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:396
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff818e7e6b-ffffffff818e7ea5: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff818e7c40-ffffffff818e7cfb: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:441
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff819bb1cc-ffffffff819bb206: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff819baf30-ffffffff819baff2: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:445
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff81c2b71d-ffffffff81c2b757: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff819bd190-ffffffff819bd252: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:445
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff81c1dbb6-ffffffff81c1dbf0: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff819a1920-ffffffff819a19e2: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:445
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff81d2f040-ffffffff81d2f0a2: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff81a4e8d0-ffffffff81a4e9a6: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:456
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff81efb504-ffffffff81efb544: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff81bbd4c0-ffffffff81bbd5d0: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:464
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff820a9e25-ffffffff820a9e4d: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff81d63150-ffffffff81d63271: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81a7d740)
Location: drivers/xen/efi.c:297
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/xen/efi.c:xen_efi_config_table_is_usable
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff81a7d740-ffffffff81a7d85f: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/efi.c (ffffffff81acfbe0)
Location: drivers/xen/efi.c:297
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/xen/efi.c:xen_efi_config_table_is_usable
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
```
**Symbols:**

```
ffffffff81acfbe0-ffffffff81acfcff: efi_mem_desc_lookup (STB_GLOBAL)
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
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff800010b5ace0)
Location: drivers/firmware/efi/efi.c:396
Inline: False
Direct callers:
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffff800010b5ace0-ffff800010b5adf0: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c0c3b870)
Location: drivers/firmware/efi/efi.c:396
Inline: False
Direct callers:
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
c0c3b870-c0c3b9ec: efi_mem_desc_lookup (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:396
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8188abeb-ffffffff8188ac25: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff8188a9c0-ffffffff8188aa7b: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:396
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff8184256b-ffffffff818425a5: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff81842340-ffffffff818423fb: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:396
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff818dcccb-ffffffff818dcd05: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff818dcaa0-ffffffff818dcb5b: efi_mem_desc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int efi_mem_desc_lookup(u64 phys_addr, efi_memory_desc_t *out_md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:396
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
**Symbols:**

```
ffffffff818f97db-ffffffff818f9815: efi_mem_desc_lookup.cold (STB_LOCAL)
ffffffff818f95b0-ffffffff818f966b: efi_mem_desc_lookup (STB_GLOBAL)
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
