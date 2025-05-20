# Function: <code>numa_set_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81074b00)
Location: arch/x86/mm/numa.c:81
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
**Symbols:**

```
ffffffff81074b00-ffffffff81074b32: numa_set_node.part.2 (STB_LOCAL)
ffffffff81074b90-ffffffff81074bb3: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81fa1612)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff81076100-ffffffff81076132: numa_set_node.part.2 (STB_LOCAL)
ffffffff81076190-ffffffff810761b3: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81fdcbe9)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu2node
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff81079cf0-ffffffff81079d22: numa_set_node.part.1 (STB_LOCAL)
ffffffff81079d80-ffffffff81079da3: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff820bdbd4)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff810785a0-ffffffff810785d2: numa_set_node.part.1 (STB_LOCAL)
ffffffff81078630-ffffffff81078653: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff826c4a0b)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff8107e8e0-ffffffff8107e912: numa_set_node.part.1 (STB_LOCAL)
ffffffff8107e990-ffffffff8107e9b3: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff826eecae)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff81081a20-ffffffff81081a52: numa_set_node.part.1 (STB_LOCAL)
ffffffff81081ad0-ffffffff81081af3: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828a599c)
Location: arch/x86/mm/numa.c:79
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff81088630-ffffffff81088662: numa_set_node.part.2 (STB_LOCAL)
ffffffff810886e0-ffffffff81088703: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828bdf71)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff8108c280-ffffffff8108c2b2: numa_set_node.part.0 (STB_LOCAL)
ffffffff8108c310-ffffffff8108c333: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828c43cb)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff8108cee0-ffffffff8108cf12: numa_set_node.part.0 (STB_LOCAL)
ffffffff8108cf70-ffffffff8108cf93: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81094560)
Location: arch/x86/mm/numa.c:77
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff81094560-ffffffff810945a6: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81093960)
Location: arch/x86/mm/numa.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff81093960-ffffffff810939a6: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81094320)
Location: arch/x86/mm/numa.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff81094320-ffffffff81094366: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810a4190)
Location: arch/x86/mm/numa.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff810a4190-ffffffff810a421e: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810b8910)
Location: arch/x86/mm/numa.c:75
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff810b8910-ffffffff810b89b2: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff83e9e4ee)
Location: arch/x86/mm/numa.c:75
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
**Symbols:**

```
ffffffff810d4190-ffffffff810d4232: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff836c264e)
Location: arch/x86/mm/numa.c:75
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
**Symbols:**

```
ffffffff810d76d0-ffffffff810d7772: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff838f304e)
Location: arch/x86/mm/numa.c:77
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
```
**Symbols:**

```
ffffffff810dff50-ffffffff810dfff2: numa_set_node (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828af3a1)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff8108bea0-ffffffff8108bed2: numa_set_node.part.0 (STB_LOCAL)
ffffffff8108bf30-ffffffff8108bf53: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828a7593)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff8107a9d0-ffffffff8107aa02: numa_set_node.part.0 (STB_LOCAL)
ffffffff8107aa60-ffffffff8107aa83: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828c22a0)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff8108be50-ffffffff8108be82: numa_set_node.part.0 (STB_LOCAL)
ffffffff8108bee0-ffffffff8108bf03: numa_set_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void numa_set_node(int cpu, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828c53eb)
Location: arch/x86/mm/numa.c:80
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/acpi/boot.c:acpi_map_cpu
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
**Symbols:**

```
ffffffff8108e1b0-ffffffff8108e1e2: numa_set_node.part.0 (STB_LOCAL)
ffffffff8108e240-ffffffff8108e263: numa_set_node (STB_GLOBAL)
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
