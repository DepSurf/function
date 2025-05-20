# Function: <code>walk_memory_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int walk_memory_range(long unsigned int start_pfn, long unsigned int end_pfn, void *arg, int (*func)(struct memory_block *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811f0390)
Location: mm/memory_hotplug.c:1869
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_unbind_memory_blocks
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff811f0390-ffffffff811f0463: walk_memory_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_memory_range(long unsigned int start_pfn, long unsigned int end_pfn, void *arg, int (*func)(struct memory_block *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120f6b0)
Location: mm/memory_hotplug.c:2020
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_unbind_memory_blocks
```
**Symbols:**

```
ffffffff8120f6b0-ffffffff8120f785: walk_memory_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_memory_range(long unsigned int start_pfn, long unsigned int end_pfn, void *arg, int (*func)(struct memory_block *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812217f0)
Location: mm/memory_hotplug.c:2008
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_unbind_memory_blocks
```
**Symbols:**

```
ffffffff812217f0-ffffffff812218c5: walk_memory_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int walk_memory_range(long unsigned int start_pfn, long unsigned int end_pfn, void *arg, int (*func)(struct memory_block *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122d410)
Location: mm/memory_hotplug.c:1772
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_unbind_memory_blocks
```
**Symbols:**

```
ffffffff8122d410-ffffffff8122d4e5: walk_memory_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_memory_range(long unsigned int start_pfn, long unsigned int end_pfn, void *arg, int (*func)(struct memory_block *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81248ca0)
Location: mm/memory_hotplug.c:1736
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_unbind_memory_blocks
```
**Symbols:**

```
ffffffff81248ca0-ffffffff81248d87: walk_memory_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int walk_memory_range(long unsigned int start_pfn, long unsigned int end_pfn, void *arg, int (*func)(struct memory_block *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126c700)
Location: mm/memory_hotplug.c:1745
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_unbind_memory_blocks
```
**Symbols:**

```
ffffffff8126c700-ffffffff8126c7dd: walk_memory_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_memory_range(long unsigned int start_pfn, long unsigned int end_pfn, void *arg, int (*func)(struct memory_block *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81280fa0)
Location: mm/memory_hotplug.c:1729
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_memory
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_unbind_memory_blocks
  - drivers/base/node.c:link_mem_sections
```
**Symbols:**

```
ffffffff81280fa0-ffffffff8128107d: walk_memory_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
</ul>
