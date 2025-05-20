# Function: <code>acpi_map_pxm_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8148b115)
Location: drivers/acpi/numa.c:69
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff8148b115-ffffffff8148b1b5: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff814d9f4f)
Location: drivers/acpi/numa.c:69
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff814d9f4f-ffffffff814d9fed: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff814fc7fb)
Location: drivers/acpi/numa.c:69
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff814fc7fb-ffffffff814fc8b0: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8150cb60)
Location: drivers/acpi/numa.c:69
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff8150cb60-ffffffff8150cc24: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8154fac0)
Location: drivers/acpi/numa.c:69
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff8154fac0-ffffffff8154fb84: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff81586360)
Location: drivers/acpi/numa.c:69
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff81586360-ffffffff81586422: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8159e670)
Location: drivers/acpi/numa.c:68
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff8159e670-ffffffff8159e732: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff815cfb70)
Location: drivers/acpi/numa.c:54
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff815cfb70-ffffffff815cfc32: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff815f0de0)
Location: drivers/acpi/numa.c:54
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff815f0de0-ffffffff815f0ea2: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff816e79e0)
Location: drivers/acpi/numa/srat.c:55
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff816e79e0-ffffffff816e7aa1: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff817052d0)
Location: drivers/acpi/numa/srat.c:60
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
```
**Symbols:**

```
ffffffff817052d0-ffffffff81705391: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff816e6980)
Location: drivers/acpi/numa/srat.c:60
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
```
**Symbols:**

```
ffffffff816e6980-ffffffff816e6a3b: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8175fe10)
Location: drivers/acpi/numa/srat.c:60
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
```
**Symbols:**

```
ffffffff8175fe10-ffffffff8175ffe4: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff818937a0)
Location: drivers/acpi/numa/srat.c:60
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
```
**Symbols:**

```
ffffffff818937a0-ffffffff818939a7: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff819db280)
Location: drivers/acpi/numa/srat.c:60
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
```
**Symbols:**

```
ffffffff819db280-ffffffff819db487: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff81a22f30)
Location: drivers/acpi/numa/srat.c:60
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
```
**Symbols:**

```
ffffffff81a22f30-ffffffff81a23137: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff81a6da30)
Location: drivers/acpi/numa/srat.c:60
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
```
**Symbols:**

```
ffffffff81a6da30-ffffffff81a6dc2c: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffff80001077b8f8)
Location: drivers/acpi/numa.c:54
Inline: True
Direct callers:
  - arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init
  - drivers/irqchip/irq-gic-v3-its.c:gic_acpi_parse_srat_its
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/arm64/iort.c:arm_smmu_v3_set_proximity
```
**Symbols:**

```
ffff80001077b8f8-ffff80001077b9f0: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
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
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff815dfa70)
Location: drivers/acpi/numa.c:54
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff815dfa70-ffffffff815dfb32: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff815cb0b0)
Location: drivers/acpi/numa.c:54
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff815cb0b0-ffffffff815cb172: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff815e50c0)
Location: drivers/acpi/numa.c:54
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff815e50c0-ffffffff815e5182: acpi_map_pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_map_pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff815fef70)
Location: drivers/acpi/numa.c:54
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff815fef70-ffffffff815ff032: acpi_map_pxm_to_node (STB_GLOBAL)
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
