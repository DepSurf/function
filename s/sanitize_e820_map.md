# Function: <code>sanitize_e820_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sanitize_e820_map(struct e820entry *biosmap, int max_nr_map, u32 *pnr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67b44)
Location: arch/x86/kernel/e820.c:260
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:update_e820
  - arch/x86/kernel/e820.c:parse_e820_ext
  - arch/x86/kernel/e820.c:early_reserve_e820
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/early-quirks.c:intel_graphics_stolen
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff81f67b44-ffffffff81f67d48: sanitize_e820_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sanitize_e820_map(struct e820entry *biosmap, int max_nr_map, u32 *pnr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8f9f5)
Location: arch/x86/kernel/e820.c:260
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/kernel/e820.c:early_reserve_e820
  - arch/x86/kernel/e820.c:parse_e820_ext
  - arch/x86/kernel/e820.c:update_e820
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff81f8f9f5-ffffffff81f8fc0f: sanitize_e820_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sanitize_e820_map(struct e820entry *biosmap, int max_nr_map, u32 *pnr_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fcadd6)
Location: arch/x86/kernel/e820.c:262
Inline: False
Direct callers:
  - arch/x86/xen/setup.c:xen_auto_xlated_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/e820.c:default_machine_specific_memory_setup
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/kernel/e820.c:early_reserve_e820
  - arch/x86/kernel/e820.c:parse_e820_ext
  - arch/x86/kernel/e820.c:update_e820
  - arch/x86/kernel/early-quirks.c:intel_graphics_quirks
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
**Symbols:**

```
ffffffff81fcadd6-ffffffff81fcaff0: sanitize_e820_map (STB_GLOBAL)
```
</details>
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
</ul>
