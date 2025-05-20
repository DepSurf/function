# Function: <code>numa_map_to_online_node</code>

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
int numa_map_to_online_node(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cc920)
Location: mm/mempolicy.c:136
Inline: True
Direct callers:
  - drivers/nvdimm/e820.c:e820_register_one
```
**Symbols:**

```
ffffffff812cc920-ffffffff812cc9d8: numa_map_to_online_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int numa_map_to_online_node(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d82c0)
Location: mm/mempolicy.c:136
Inline: True
Direct callers:
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff812d82c0-ffffffff812d8378: numa_map_to_online_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int numa_map_to_online_node(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812df330)
Location: mm/mempolicy.c:136
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff812df330-ffffffff812df3e0: numa_map_to_online_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int numa_map_to_online_node(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81326c90)
Location: mm/mempolicy.c:138
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff81326c90-ffffffff81326d40: numa_map_to_online_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int numa_map_to_online_node(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81395620)
Location: mm/mempolicy.c:141
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff81395620-ffffffff813956f4: numa_map_to_online_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int numa_map_to_online_node(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814155d0)
Location: mm/mempolicy.c:141
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
  - drivers/dax/hmem/device.c:hmem_register_device
```
**Symbols:**

```
ffffffff814155d0-ffffffff8141568c: numa_map_to_online_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int numa_map_to_online_node(int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81448bb0)
Location: mm/mempolicy.c:141
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - drivers/nvdimm/e820.c:e820_register_one
```
**Symbols:**

```
ffffffff81448bb0-ffffffff81448c6c: numa_map_to_online_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
