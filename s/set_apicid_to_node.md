# Function: <code>set_apicid_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104f528)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff81f789fa)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f79320)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff81f794b2)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104fb18)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/mm/numa.c (ffffffff81fa119c)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa1a70)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff81fa1b63)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81052288)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/mm/numa.c (ffffffff81fdc8d7)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fdd051)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff81fdd146)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051e58)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/mm/numa.c (ffffffff820bd90a)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff820bdfb3)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff820be141)
Location: arch/x86/include/asm/numa.h:36
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81055ac8)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
```
```
In arch/x86/mm/numa.c (ffffffff826c4741)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff826c4ded)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff826c4f81)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81058945)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff826ee9e3)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff826ef141)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff826ef2bd)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8105e565)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828a56d1)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a5e2f)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828a5fab)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81061975)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828bdc6a)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff828be3fc)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828be59e)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81062205)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828c40f4)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c4860)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828c4a31)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810681b5)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff82ce7bce)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff82ce7d9f)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81069eb5)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff82fd55c5)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff82fd5796)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8106a985)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (0)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff831e006b)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff831e0241)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81075233)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff832c302f)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c3693)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff832c38af)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81083be3)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff834758b0)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff83475f28)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff8347616a)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810969a3)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff83e9e35b)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff83e9ec6f)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff83e9effc)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81099ac3)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff836c24bb)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff836c2de3)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff836c317c)
Location: arch/x86/include/asm/numa.h:38
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810a12f3)
Location: arch/x86/include/asm/numa.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff838f2ebb)
Location: arch/x86/include/asm/numa.h:31
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff838f39d3)
Location: arch/x86/include/asm/numa.h:31
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff838f3d5c)
Location: arch/x86/include/asm/numa.h:31
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81061d85)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828af0ca)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff828af836)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828af9d8)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81052155)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828a72bc)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a7a28)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828a7bca)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810621a5)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828c1fc9)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c2735)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828c28d7)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81063765)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/boot.c:acpi_unmap_cpu
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
```
In arch/x86/mm/numa.c (ffffffff828c5114)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c5880)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828c5a51)
Location: arch/x86/include/asm/numa.h:37
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
</details>
</li>
</ul>

## Differences
