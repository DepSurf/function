# Function: <code>pxm_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8148b0dd)
Location: drivers/acpi/numa.c:47
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_slit_init
  - arch/x86/mm/srat.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff8148b0dd-ffffffff8148b0f9: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff81fce8be)
Location: drivers/acpi/numa.c:47
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff814d9f17-ffffffff814d9f33: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8200bc7f)
Location: drivers/acpi/numa.c:47
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff814fc7c3-ffffffff814fc7df: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff820ed468)
Location: drivers/acpi/numa.c:47
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff8150cb20-ffffffff8150cb40: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff826f63c9)
Location: drivers/acpi/numa.c:47
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff8154fa80-ffffffff8154faa0: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff827203ee)
Location: drivers/acpi/numa.c:47
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff81586320-ffffffff81586340: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828d8384)
Location: drivers/acpi/numa.c:46
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff8159e630-ffffffff8159e650: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828f223c)
Location: drivers/acpi/numa.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_init
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff815cfd90-ffffffff815cfdb0: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828fb431)
Location: drivers/acpi/numa.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff815f1000-ffffffff815f1020: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff82d13695)
Location: drivers/acpi/numa/srat.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
**Symbols:**

```
ffffffff816e79b0-ffffffff816e79d0: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff81705288)
Location: drivers/acpi/numa/srat.c:37
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:alloc_memory_initiator
  - drivers/acpi/numa/hmat.c:alloc_memory_initiator
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff817051f0-ffffffff8170521e: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff816e6938)
Location: drivers/acpi/numa/srat.c:37
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff816e68a0-ffffffff816e68ce: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8175fda8)
Location: drivers/acpi/numa/srat.c:37
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff8175fcf0-ffffffff8175fd3c: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8189372f)
Location: drivers/acpi/numa/srat.c:37
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff81893670-ffffffff818936cc: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff819db1ff)
Location: drivers/acpi/numa/srat.c:37
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff819db130-ffffffff819db18c: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff81a22eaf)
Location: drivers/acpi/numa/srat.c:37
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff81a22de0-ffffffff81a22e3c: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff81a6dc9f)
Location: drivers/acpi/numa/srat.c:37
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
  - drivers/acpi/numa/srat.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target
  - drivers/acpi/numa/hmat.c:hmat_register_target
  - drivers/acpi/numa/hmat.c:hmat_register_target
  - drivers/acpi/numa/hmat.c:hmat_register_target
  - drivers/acpi/numa/hmat.c:hmat_register_target
  - drivers/acpi/numa/hmat.c:__hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:__hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
**Symbols:**

```
ffffffff81a6d9c0-ffffffff81a6da1c: pxm_to_node (STB_GLOBAL)
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
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffff80001147e494)
Location: drivers/acpi/numa.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
Direct callers:
  - arch/arm64/kernel/acpi_numa.c:acpi_parse_gicc_pxm
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffff80001077bbb0-ffff80001077bbec: pxm_to_node (STB_GLOBAL)
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
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828e40c5)
Location: drivers/acpi/numa.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff815dfc90-ffffffff815dfcb0: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828dc16c)
Location: drivers/acpi/numa.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff815cb2d0-ffffffff815cb2f0: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828f702d)
Location: drivers/acpi/numa.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
```
**Symbols:**

```
ffffffff815e52e0-ffffffff815e5300: pxm_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pxm_to_node(int pxm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828fc485)
Location: drivers/acpi/numa.c:32
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_slit_init
  - drivers/acpi/numa.c:acpi_numa_slit_init
Direct callers:
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_register_target_initiators
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
  - drivers/acpi/hmat/hmat.c:hmat_parse_subtable
```
**Symbols:**

```
ffffffff815ff190-ffffffff815ff1b0: pxm_to_node (STB_GLOBAL)
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
