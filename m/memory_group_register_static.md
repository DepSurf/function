# Function: <code>memory_group_register_static</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memory_group_register_static(int nid, long unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185ce80)
Location: drivers/base/memory.c:964
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff8185ce80-ffffffff8185cecc: memory_group_register_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memory_group_register_static(int nid, long unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a4100)
Location: drivers/base/memory.c:1060
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff819a4100-ffffffff819a4172: memory_group_register_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memory_group_register_static(int nid, long unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16100)
Location: drivers/base/memory.c:1067
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff81b16100-ffffffff81b16172: memory_group_register_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memory_group_register_static(int nid, long unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b64e70)
Location: drivers/base/memory.c:1062
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff81b64e70-ffffffff81b64ee2: memory_group_register_static (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memory_group_register_static(int nid, long unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb8bd0)
Location: drivers/base/memory.c:1115
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
```
**Symbols:**

```
ffffffff81bb8bd0-ffffffff81bb8c42: memory_group_register_static (STB_GLOBAL)
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
