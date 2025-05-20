# Function: <code>pat_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff8106f910)
Location: arch/x86/mm/pat.c:56
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:track_pfn_remap
Direct callers:
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8106f910-ffffffff8106f926: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81070762)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:track_pfn_remap
Direct callers:
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff8106f610-ffffffff8106f626: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810743f2)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:track_pfn_remap
Direct callers:
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
  - arch/x86/pci/i386.c:pci_mmap_page_range
```
**Symbols:**

```
ffffffff81073240-ffffffff81073256: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff81072840)
Location: arch/x86/mm/pat.c:66
Inline: True
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81072840-ffffffff81072852: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff810781a0)
Location: arch/x86/mm/pat.c:66
Inline: True
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff810781a0-ffffffff810781b2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff826edbd4)
Location: arch/x86/mm/pat.c:66
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff8107ad00-ffffffff8107ad12: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff828a48f8)
Location: arch/x86/mm/pat.c:66
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81081640-ffffffff81081652: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff828bcdcf)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff810852e0-ffffffff810852f2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff828c3264)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81085fd0-ffffffff81085fe2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff82ce6a4d)
Location: arch/x86/mm/pat/memtype.c:93
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff8108f6c0-ffffffff8108f6d2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff82fd4393)
Location: arch/x86/mm/pat/memtype.c:93
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff8108f3b0-ffffffff8108f3c2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff831dee9c)
Location: arch/x86/mm/pat/memtype.c:93
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pat/memtype.c:untrack_pfn
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat/memtype.c:memtype_reserve_io
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff8108ff40-ffffffff8108ff52: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810a0a75)
Location: arch/x86/mm/pat/memtype.c:93
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81ca1434-ffffffff81ca1454: pat_enabled.cold (STB_LOCAL)
ffffffff8109fbc0-ffffffff8109fbd8: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff810b4a65)
Location: arch/x86/mm/pat/memtype.c:95
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81e50a3c-ffffffff81e50a66: pat_enabled.cold (STB_LOCAL)
ffffffff810b3b80-ffffffff810b3ba2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff83e9cd05)
Location: arch/x86/mm/pat/memtype.c:89
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff82054eee-ffffffff82054f1b: pat_enabled.cold (STB_LOCAL)
ffffffff810ce820-ffffffff810ce845: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff836c0825)
Location: arch/x86/mm/pat/memtype.c:89
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff820d34bd-ffffffff820d34ea: pat_enabled.cold (STB_LOCAL)
ffffffff810d1de0-ffffffff810d1e05: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype.c (ffffffff838f1345)
Location: arch/x86/mm/pat/memtype.c:89
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_memtype_list_init
  - arch/x86/mm/pat/memtype.c:track_pfn_insert
  - arch/x86/mm/pat/memtype.c:track_pfn_remap
  - arch/x86/mm/pat/memtype.c:reserve_pfn_range
  - arch/x86/mm/pat/memtype.c:memtype_free
  - arch/x86/mm/pat/memtype.c:memtype_reserve
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_create_resource_files
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff821ae32b-ffffffff821ae358: pat_enabled.cold (STB_LOCAL)
ffffffff810da510-ffffffff810da535: pat_enabled (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff828ae23a)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81084fd0-ffffffff81084fe2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff828a642c)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81073ca0-ffffffff81073cb2: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff828c1139)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff81084f80-ffffffff81084f92: pat_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool pat_enabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat.c (ffffffff828c4284)
Location: arch/x86/mm/pat.c:67
Inline: True
Inline callers:
  - arch/x86/mm/pat.c:pat_memtype_list_init
  - arch/x86/mm/pat.c:untrack_pfn
  - arch/x86/mm/pat.c:track_pfn_insert
  - arch/x86/mm/pat.c:track_pfn_remap
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:reserve_pfn_range
  - arch/x86/mm/pat.c:arch_io_free_memtype_wc
  - arch/x86/mm/pat.c:io_reserve_memtype
  - arch/x86/mm/pat.c:reserve_memtype
Direct callers:
  - drivers/pci/proc.c:proc_bus_pci_ioctl
```
**Symbols:**

```
ffffffff810870d0-ffffffff810870e2: pat_enabled (STB_GLOBAL)
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
