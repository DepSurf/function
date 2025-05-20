# Function: <code>acpi_map_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104f860)
Location: arch/x86/kernel/acpi/boot.c:714
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff8104f860-ffffffff8104f8d2: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8104f990)
Location: arch/x86/kernel/acpi/boot.c:721
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff8104f990-ffffffff8104fa07: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81052340)
Location: arch/x86/kernel/acpi/boot.c:726
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81052340-ffffffff810523a4: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81051cd0)
Location: arch/x86/kernel/acpi/boot.c:741
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81051cd0-ffffffff81051d44: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81055940)
Location: arch/x86/kernel/acpi/boot.c:759
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81055940-ffffffff810559b4: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff815789c0)
Location: arch/x86/kernel/acpi/boot.c:765
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81058a57-ffffffff81058a68: acpi_map_cpu.cold.7 (STB_LOCAL)
ffffffff810587c0-ffffffff81058829: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81590630)
Location: arch/x86/kernel/acpi/boot.c:766
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8105e698-ffffffff8105e6a9: acpi_map_cpu.cold.9 (STB_LOCAL)
ffffffff8105e3e0-ffffffff8105e449: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff815c1470)
Location: arch/x86/kernel/acpi/boot.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81061a98-ffffffff81061aa9: acpi_map_cpu.cold (STB_LOCAL)
ffffffff810617f0-ffffffff8106185b: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff815e2710)
Location: arch/x86/kernel/acpi/boot.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81062348-ffffffff81062359: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81062080-ffffffff810620eb: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8168de70)
Location: arch/x86/kernel/acpi/boot.c:750
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81068308-ffffffff81068319: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81067fb0-ffffffff8106801b: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff816abc50)
Location: arch/x86/kernel/acpi/boot.c:750
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81bd667c-ffffffff81bd668d: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81069cb0-ffffffff81069d1b: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff8168e3a0)
Location: arch/x86/kernel/acpi/boot.c:750
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81bc892e-ffffffff81bc893f: acpi_map_cpu.cold (STB_LOCAL)
ffffffff8106a780-ffffffff8106a7eb: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81703c00)
Location: arch/x86/kernel/acpi/boot.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81c9d11e-ffffffff81c9d12f: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81074ff0-ffffffff81075085: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81831c60)
Location: arch/x86/kernel/acpi/boot.c:816
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81e4c512-ffffffff81e4c523: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81083c70-ffffffff81083d0f: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81096a40)
Location: arch/x86/kernel/acpi/boot.c:829
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81096a40-ffffffff81096b02: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff81099b60)
Location: arch/x86/kernel/acpi/boot.c:838
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81099b60-ffffffff81099c22: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff810a1390)
Location: arch/x86/kernel/acpi/boot.c:847
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810a1390-ffffffff810a1452: acpi_map_cpu (STB_GLOBAL)
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
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffff80001076f148)
Location: drivers/acpi/acpi_processor.c:165
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffff80001076f148-ffff80001076f164: acpi_map_cpu (STB_WEAK)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff815d49d0)
Location: arch/x86/kernel/acpi/boot.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81061ec8-ffffffff81061ed9: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81061c00-ffffffff81061c6b: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff815be590)
Location: arch/x86/kernel/acpi/boot.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81052298-ffffffff810522a9: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81051fd0-ffffffff8105203b: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff815d69f0)
Location: arch/x86/kernel/acpi/boot.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810622e8-ffffffff810622f9: acpi_map_cpu.cold (STB_LOCAL)
ffffffff81062020-ffffffff8106208b: acpi_map_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_map_cpu(acpi_handle handle, phys_cpuid_t physid, u32 acpi_id, int *pcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/boot.c (ffffffff815f08b0)
Location: arch/x86/kernel/acpi/boot.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810638a8-ffffffff810638b9: acpi_map_cpu.cold (STB_LOCAL)
ffffffff810635e0-ffffffff8106364b: acpi_map_cpu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 acpi_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, physid, pcpu</code> ➡️ <code>handle, physid, acpi_id, pcpu</code>
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
