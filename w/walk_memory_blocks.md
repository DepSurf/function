# Function: <code>walk_memory_blocks</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f9200)
Location: drivers/base/memory.c:860
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff816f9200-ffffffff816f92af: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171d580)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff8171d580-ffffffff8171d62f: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d9420)
Location: drivers/base/memory.c:774
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff817d9420-ffffffff817d94d3: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817eddc0)
Location: drivers/base/memory.c:765
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff817eddc0-ffffffff817ede73: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d2710)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff817d2710-ffffffff817d27c3: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185d860)
Location: drivers/base/memory.c:856
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff8185d860-ffffffff8185d913: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a4cd0)
Location: drivers/base/memory.c:952
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/node.c:node_dev_init
```
**Symbols:**

```
ffffffff819a4cd0-ffffffff819a4d89: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16dc0)
Location: drivers/base/memory.c:959
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/node.c:node_dev_init
```
**Symbols:**

```
ffffffff81b16dc0-ffffffff81b16e79: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b65b30)
Location: drivers/base/memory.c:954
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/node.c:node_dev_init
```
**Symbols:**

```
ffffffff81b65b30-ffffffff81b65be9: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb99b0)
Location: drivers/base/memory.c:1007
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:offline_and_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/node.c:node_dev_init
```
**Symbols:**

```
ffffffff81bb99b0-ffffffff81bb9a69: walk_memory_blocks (STB_GLOBAL)
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010911238)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffff800010911238-ffff800010911320: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b2660)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
c0000000009b2660-c0000000009b27b8: walk_memory_blocks (STB_GLOBAL)
```
</details>
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
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e38b0)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff816e38b0-ffffffff816e395f: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdef0)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff816bdef0-ffffffff816bdf9f: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81710a40)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff81710a40-ffffffff81710aef: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_memory_blocks(long unsigned int start, long unsigned int size, void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172bba0)
Location: drivers/base/memory.c:834
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff8172bba0-ffffffff8172bc4f: walk_memory_blocks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
