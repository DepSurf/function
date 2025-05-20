# Function: <code>arch_register_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81035ba0)
Location: arch/x86/kernel/topology.c:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81035ba0-ffffffff81035cb9: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81034d90)
Location: arch/x86/kernel/topology.c:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81034d90-ffffffff81034ea9: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81034aa0)
Location: arch/x86/kernel/topology.c:107
Inline: True
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
**Symbols:**

```
ffffffff81034aa0-ffffffff81034bb6: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81032ad0)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81032ad0-ffffffff81032be6: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81034e00)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81034e00-ffffffff81034f16: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81035f80)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81035f80-ffffffff81036096: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81037170)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81037170-ffffffff81037290: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81039380)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81039380-ffffffff81039498: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81039b50)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81039b50-ffffffff81039c68: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff8103c6f0)
Location: arch/x86/kernel/topology.c:97
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8103c6f0-ffffffff8103c816: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff8103cb90)
Location: arch/x86/kernel/topology.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8103cb90-ffffffff8103ccb3: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff8103e480)
Location: arch/x86/kernel/topology.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8103e480-ffffffff8103e5a3: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81044150)
Location: arch/x86/kernel/topology.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81044150-ffffffff810442c1: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff8104c300)
Location: arch/x86/kernel/topology.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8104c300-ffffffff8104c482: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81058440)
Location: arch/x86/kernel/topology.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81058440-ffffffff810585b9: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int arch_register_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff8369af9b)
Location: arch/x86/kernel/topology.c:41
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810595e0-ffffffff81059642: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_register_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cpu.c (ffffffff81b96490)
Location: drivers/base/cpu.c:535
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/base/cpu.c:cpu_dev_init
```
**Symbols:**

```
ffffffff81b96490-ffffffff81b964f5: arch_register_cpu (STB_WEAK)
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
int arch_register_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:176
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffff80001076f188-ffff80001076f1a4: arch_register_cpu (STB_WEAK)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81039cb0)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81039cb0-ffffffff81039dc8: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff810295c0)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff810295c0-ffffffff810296d8: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff81039b10)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff81039b10-ffffffff81039c28: arch_register_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_register_cpu(int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff8103ab10)
Location: arch/x86/kernel/topology.c:107
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_arch_register_cpu
  - arch/x86/kernel/topology.c:topology_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
```
**Symbols:**

```
ffffffff8103ab10-ffffffff8103ac28: arch_register_cpu (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>int num</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>int num</code>
</li>
</ul>
</details>
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
