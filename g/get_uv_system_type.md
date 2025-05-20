# Function: <code>get_uv_system_type</code>

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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
```
```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
```
```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
```
```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
```
```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:24
Inline: True
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
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:25
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d8d0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:328
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff8106d8d0-ffffffff8106d8e1: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074ba0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:354
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff81074ba0-ffffffff81074bb1: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810754f0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:500
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff810754f0-ffffffff81075501: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075f90)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:496
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff81075f90-ffffffff81075fa1: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81083590)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:496
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff81083590-ffffffff810835a1: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81093440)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:502
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff81093440-ffffffff81093455: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a8980)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:502
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff810a8980-ffffffff810a8995: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810abbb0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:502
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff810abbb0-ffffffff810abbc5: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2a20)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:503
Inline: False
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff810b2a20-ffffffff810b2a35: get_uv_system_type (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:32
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:32
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/srat.c (0)
Location: arch/x86/include/asm/uv/uv.h:32
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum uv_system_type get_uv_system_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106efa0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:328
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
```
**Symbols:**

```
ffffffff8106efa0-ffffffff8106efb1: get_uv_system_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
