# Function: <code>srat_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/srat.c (0)
Location: arch/x86/mm/srat.c:40
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff81fce87b)
Location: drivers/acpi/numa.c:221
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
**Symbols:**

```
ffffffff81fce87b-ffffffff81fce88a: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8200bc3c)
Location: drivers/acpi/numa.c:221
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
**Symbols:**

```
ffffffff8200bc3c-ffffffff8200bc4b: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff820ed40c)
Location: drivers/acpi/numa.c:221
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
**Symbols:**

```
ffffffff820ed40c-ffffffff820ed420: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff826f636d)
Location: drivers/acpi/numa.c:223
Inline: True
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
**Symbols:**

```
ffffffff826f636d-ffffffff826f6381: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff8272048f)
Location: drivers/acpi/numa.c:223
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
**Symbols:**

```
ffffffff82720392-ffffffff827203a6: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828d8425)
Location: drivers/acpi/numa.c:222
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
**Symbols:**

```
ffffffff828d8328-ffffffff828d833c: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828f22da)
Location: drivers/acpi/numa.c:209
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828f21e0-ffffffff828f21f4: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828fb4cf)
Location: drivers/acpi/numa.c:209
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828fb3d5-ffffffff828fb3e9: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff82d13733)
Location: drivers/acpi/numa/srat.c:169
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff82d13639-ffffffff82d1364d: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8300132e)
Location: drivers/acpi/numa/srat.c:204
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff8300121a-ffffffff8300122e: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8320c41e)
Location: drivers/acpi/numa/srat.c:204
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff8320c30a-ffffffff8320c31e: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff832f4bdd)
Location: drivers/acpi/numa/srat.c:204
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff832f4a84-ffffffff832f4a98: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff834acf5e)
Location: drivers/acpi/numa/srat.c:204
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff834acddf-ffffffff834acdf7: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff83ee5c15)
Location: drivers/acpi/numa/srat.c:204
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff83ee59e0-ffffffff83ee59f8: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8370b5e5)
Location: drivers/acpi/numa/srat.c:204
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff8370b3b0-ffffffff8370b3c8: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa/srat.c (ffffffff8393ea75)
Location: drivers/acpi/numa/srat.c:204
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/numa/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff8393e840-ffffffff8393e858: srat_disabled (STB_GLOBAL)
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
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffff80001147e5ac)
Location: drivers/acpi/numa.c:209
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/arm64/kernel/acpi_numa.c:arm64_acpi_numa_init
  - arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init
  - arch/arm64/kernel/acpi_numa.c:acpi_parse_gicc_pxm
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffff80001147e418-ffff80001147e43c: srat_disabled (STB_GLOBAL)
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
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828e4163)
Location: drivers/acpi/numa.c:209
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828e4069-ffffffff828e407d: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828dc20a)
Location: drivers/acpi/numa.c:209
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828dc110-ffffffff828dc124: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828f70cb)
Location: drivers/acpi/numa.c:209
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
**Symbols:**

```
ffffffff828f6fd1-ffffffff828f6fe5: srat_disabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int srat_disabled();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/numa.c (ffffffff828fc523)
Location: drivers/acpi/numa.c:209
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
Direct callers:
  - arch/x86/mm/srat.c:x86_acpi_numa_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - drivers/acpi/hmat/hmat.c:hmat_init
```
**Symbols:**

```
ffffffff828fc429-ffffffff828fc43d: srat_disabled (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
