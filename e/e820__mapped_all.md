# Function: <code>e820__mapped_all</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab455)
Location: arch/x86/kernel/e820.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff820ab455-ffffffff820ab4b5: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b1bfa)
Location: arch/x86/kernel/e820.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff826b1bfa-ffffffff826b1c8b: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826db2d1)
Location: arch/x86/kernel/e820.c:135
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff826db2d1-ffffffff826db362: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828916b8)
Location: arch/x86/kernel/e820.c:134
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff828916b8-ffffffff82891749: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a8c30)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff828a8c30-ffffffff828a8cc1: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828abc94)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff828abc94-ffffffff828abd25: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd101a)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff82cd101a-ffffffff82cd1030: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbce5a)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff82fbce5a-ffffffff82fbce70: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c756b)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff831c756b-ffffffff831c7581: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a845f)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff832a845f-ffffffff832a8475: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff834578ed)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff834578ed-ffffffff8345790d: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e76340)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff83e76340-ffffffff83e76360: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83698250)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff83698250-ffffffff83698270: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838c7fd0)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff838c7fd0-ffffffff838c7ff0: e820__mapped_all (STB_GLOBAL)
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
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82899ca6)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff82899ca6-ffffffff82899d37: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891f64)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff82891f64-ffffffff82891ff5: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828acc86)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff828acc86-ffffffff828acd17: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828acca4)
Location: arch/x86/kernel/e820.c:148
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_hvm_guest_init
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff828acca4-ffffffff828acd35: e820__mapped_all (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
