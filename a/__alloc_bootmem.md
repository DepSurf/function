# Function: <code>__alloc_bootmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8aed8)
Location: mm/nobootmem.c:308
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:spp_getpage
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81f8aed8-ffffffff81f8aef9: __alloc_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb4b1b)
Location: mm/nobootmem.c:309
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:spp_getpage
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81fb4b1b-ffffffff81fb4b3c: __alloc_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff1501)
Location: mm/nobootmem.c:312
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820_reserve_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:spp_getpage
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81ff1501-ffffffff81ff1522: __alloc_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d3986)
Location: mm/nobootmem.c:296
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:spp_getpage
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff820d3986-ffffffff820d39ac: __alloc_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc3a6)
Location: mm/nobootmem.c:297
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:spp_getpage
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff826dc3a6-ffffffff826dc3cc: __alloc_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__alloc_bootmem(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff82706864)
Location: mm/nobootmem.c:297
Inline: False
Direct callers:
  - init/main.c:initcall_blacklist
  - init/main.c:initcall_blacklist
  - arch/x86/xen/p2m.c:alloc_p2m_page
  - arch/x86/kernel/e820.c:e820__reserve_resources
  - arch/x86/kernel/acpi/boot.c:acpi_parse_hpet
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/kernel/apic/io_apic.c:io_apic_init_mappings
  - arch/x86/mm/init_64.c:spp_getpage
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff82706864-ffffffff8270689d: __alloc_bootmem (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
