# Function: <code>cc_mkenc</code>

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
u64 cc_mkenc(u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81002a90)
Location: arch/x86/coco/core.c:99
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt_amd.c:sme_early_init
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
```
**Symbols:**

```
ffffffff81002a90-ffffffff81002ad2: cc_mkenc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 cc_mkenc(u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff810033e0)
Location: arch/x86/coco/core.c:99
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/pgprot.c:add_encrypt_protection_map
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
```
**Symbols:**

```
ffffffff810033e0-ffffffff81003422: cc_mkenc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 cc_mkenc(u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81002a90)
Location: arch/x86/coco/core.c:113
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/pgprot.c:add_encrypt_protection_map
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
```
**Symbols:**

```
ffffffff81002a90-ffffffff81002ae9: cc_mkenc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 cc_mkenc(u64 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/core.c (ffffffff81002ae0)
Location: arch/x86/coco/core.c:113
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/kernel/apic/io_apic.c:io_apic_set_fixmap
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
  - arch/x86/mm/pgprot.c:add_encrypt_protection_map
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/platform/efi/quirks.c:efi_arch_mem_reserve
  - fs/proc/vmcore.c:remap_oldmem_pfn_range
```
**Symbols:**

```
ffffffff81002ae0-ffffffff81002b39: cc_mkenc (STB_GLOBAL)
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
