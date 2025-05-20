# Function: <code>__remove_memory</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a221a0)
Location: mm/memory_hotplug.c:1853
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff81a221a0-ffffffff81a22263: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129d430)
Location: mm/memory_hotplug.c:1812
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff8129d430-ffffffff8129d446: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812acc00)
Location: mm/memory_hotplug.c:1802
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff812acc00-ffffffff812acc16: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e1c10)
Location: mm/memory_hotplug.c:1811
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory
```
**Symbols:**

```
ffffffff812e1c10-ffffffff812e1c26: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ecb50)
Location: mm/memory_hotplug.c:1773
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_remove_memory
```
**Symbols:**

```
ffffffff812ecb50-ffffffff812ecb66: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c76d0)
Location: mm/memory_hotplug.c:2057
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff812c76d0-ffffffff812c76e6: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130c490)
Location: mm/memory_hotplug.c:2229
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff8130c490-ffffffff8130c4a6: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813752d0)
Location: mm/memory_hotplug.c:2151
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff813752d0-ffffffff813752f0: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2d00)
Location: mm/memory_hotplug.c:2147
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff813f2d00-ffffffff813f2d20: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81426740)
Location: mm/memory_hotplug.c:2120
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff81426740-ffffffff81426760: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81453900)
Location: mm/memory_hotplug.c:2313
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff81453900-ffffffff81453920: __remove_memory (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/linux/memory_hotplug.h:343
Inline: True
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
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042f110)
Location: mm/memory_hotplug.c:1802
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
  - arch/powerpc/platforms/pseries/hotplug-memory.c:pseries_remove_memblock
```
**Symbols:**

```
c00000000042f110-c00000000042f14c: __remove_memory (STB_GLOBAL)
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
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a51e0)
Location: mm/memory_hotplug.c:1802
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff812a51e0-ffffffff812a51f6: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81296cb0)
Location: mm/memory_hotplug.c:1802
Inline: False
```
**Symbols:**

```
ffffffff81296cb0-ffffffff81296cc6: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a2ff0)
Location: mm/memory_hotplug.c:1802
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff812a2ff0-ffffffff812a3006: __remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b3280)
Location: mm/memory_hotplug.c:1802
Inline: False
Direct callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_remove
```
**Symbols:**

```
ffffffff812b3280-ffffffff812b3296: __remove_memory (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start, size</code> ➡️ <code>start, size</code>
</li>
</ul>
</details>
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
