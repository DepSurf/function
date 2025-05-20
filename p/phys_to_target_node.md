# Function: <code>phys_to_target_node</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81094480)
Location: arch/x86/mm/numa.c:909
Inline: True
Direct callers:
  - drivers/nvdimm/e820.c:e820_register_one
```
**Symbols:**

```
ffffffff81094480-ffffffff81094507: phys_to_target_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81093880)
Location: arch/x86/mm/numa.c:928
Inline: True
Direct callers:
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff81093880-ffffffff81093907: phys_to_target_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81094240)
Location: arch/x86/mm/numa.c:934
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff81094240-ffffffff810942c7: phys_to_target_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810a4070)
Location: arch/x86/mm/numa.c:933
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff810a4070-ffffffff810a40f7: phys_to_target_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810b87c0)
Location: arch/x86/mm/numa.c:940
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff810b87c0-ffffffff810b8865: phys_to_target_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810d4020)
Location: arch/x86/mm/numa.c:940
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff810d4020-ffffffff810d40c5: phys_to_target_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810d7470)
Location: arch/x86/mm/numa.c:940
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff810d7470-ffffffff810d7605: phys_to_target_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int phys_to_target_node(phys_addr_t start);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810dfcf0)
Location: arch/x86/mm/numa.c:907
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_one
```
**Symbols:**

```
ffffffff810dfcf0-ffffffff810dfe85: phys_to_target_node (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
