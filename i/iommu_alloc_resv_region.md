# Function: <code>iommu_alloc_resv_region</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815ab324)
Location: drivers/iommu/iommu.c:1715
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff815ab900-ffffffff815ab955: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c0ed1)
Location: drivers/iommu/iommu.c:1807
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff815c15d0-ffffffff815c1625: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627661)
Location: drivers/iommu/iommu.c:1830
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81627d90-ffffffff81627de5: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816620d5)
Location: drivers/iommu/iommu.c:1836
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81662950-ffffffff816629a5: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680bb0)
Location: drivers/iommu/iommu.c:1893
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81680bb0-ffffffff81680c05: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b8400)
Location: drivers/iommu/iommu.c:2114
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff816b8400-ffffffff816b8455: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816db160)
Location: drivers/iommu/iommu.c:2172
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff816db160-ffffffff816db1b5: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f4b8)
Location: drivers/iommu/iommu.c:2535
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff8178dfd0-ffffffff8178e025: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817ba04c)
Location: drivers/iommu/iommu.c:2758
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff817b9d40-ffffffff817b9d95: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179d8ac)
Location: drivers/iommu/iommu.c:2744
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff8179cfb0-ffffffff8179d005: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff818268ac)
Location: drivers/iommu/iommu.c:2829
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
```
**Symbols:**

```
ffffffff81825c80-ffffffff81825cd5: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965e4c)
Location: drivers/iommu/iommu.c:2606
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
```
**Symbols:**

```
ffffffff81965920-ffffffff81965981: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acf5dc)
Location: drivers/iommu/iommu.c:2667
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
```
**Symbols:**

```
ffffffff81aceda0-ffffffff81acee71: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1ebac)
Location: drivers/iommu/iommu.c:2673
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
```
**Symbols:**

```
ffffffff81b1d910-ffffffff81b1d9e1: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b751c9)
Location: drivers/iommu/iommu.c:2949
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd/iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel/iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
```
**Symbols:**

```
ffffffff81b74350-ffffffff81b7443d: iommu_alloc_resv_region (STB_GLOBAL)
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
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c70f0)
Location: drivers/iommu/iommu.c:2172
Inline: False
Direct callers:
  - drivers/acpi/arm64/iort.c:iort_iommu_msi_get_resv_regions
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/arm-smmu.c:arm_smmu_get_resv_regions
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_add_device
  - drivers/iommu/virtio-iommu.c:viommu_add_device
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
```
**Symbols:**

```
ffff8000108c70f0-ffff8000108c7150: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09be0bc)
Location: drivers/iommu/iommu.c:2172
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
c09be0bc-c09be114: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096d8d8)
Location: drivers/iommu/iommu.c:2172
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
c00000000096e4c0-c00000000096e558: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
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
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0bb0)
Location: drivers/iommu/iommu.c:2172
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff816a0bb0-ffffffff816a0c05: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e5a0)
Location: drivers/iommu/iommu.c:2172
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff8167e5a0-ffffffff8167e5f5: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cee20)
Location: drivers/iommu/iommu.c:2172
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff816cee20-ffffffff816cee75: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct iommu_resv_region *iommu_alloc_resv_region(phys_addr_t start, size_t length, int prot, enum iommu_resv_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e9390)
Location: drivers/iommu/iommu.c:2172
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/amd_iommu.c:amd_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
  - drivers/iommu/intel-iommu.c:intel_iommu_get_resv_regions
```
**Symbols:**

```
ffffffff816e9390-ffffffff816e93e5: iommu_alloc_resv_region (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int type</code> ➡️ <code>enum iommu_resv_type type</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
