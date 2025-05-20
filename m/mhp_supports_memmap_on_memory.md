# Function: <code>mhp_supports_memmap_on_memory</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2d2d6)
Location: mm/memory_hotplug.c:1155
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffffffff812c7230-ffffffff812c727a: mhp_supports_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1311
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff81cbe72a-ffffffff81cbe754: mhp_supports_memmap_on_memory.cold (STB_LOCAL)
ffffffff8130bf90-ffffffff8130bfff: mhp_supports_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1277
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff81e7072f-ffffffff81e70744: mhp_supports_memmap_on_memory.cold (STB_LOCAL)
ffffffff81374f70-ffffffff81374fda: mhp_supports_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1275
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff820657bd-ffffffff820657d2: mhp_supports_memmap_on_memory.cold (STB_LOCAL)
ffffffff813f2910-ffffffff813f297a: mhp_supports_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mhp_supports_memmap_on_memory(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1250
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff820e4fae-ffffffff820e4fc3: mhp_supports_memmap_on_memory.cold (STB_LOCAL)
ffffffff81426350-ffffffff814263ba: mhp_supports_memmap_on_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82229938)
Location: mm/memory_hotplug.c:1340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
