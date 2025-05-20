# Function: <code>__add_memory</code>

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
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a22080)
Location: mm/memory_hotplug.c:1164
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81a22080-ffffffff81a22193: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91ee0)
Location: mm/memory_hotplug.c:1147
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81a91ee0-ffffffff81a91fab: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac9670)
Location: mm/memory_hotplug.c:1122
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81ac9670-ffffffff81ac973b: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc1df0)
Location: mm/memory_hotplug.c:1108
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81bc1df0-ffffffff81bc1e62: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3aeb0)
Location: mm/memory_hotplug.c:1119
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81c3aeb0-ffffffff81c3af30: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2d4f0)
Location: mm/memory_hotplug.c:1300
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81c2d4f0-ffffffff81c2d570: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4bdc0)
Location: mm/memory_hotplug.c:1466
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81d4bdc0-ffffffff81d4be40: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1b670)
Location: mm/memory_hotplug.c:1434
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81f1b670-ffffffff81f1b710: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c35f0)
Location: mm/memory_hotplug.c:1432
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff820c35f0-ffffffff820c3690: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff821473d0)
Location: mm/memory_hotplug.c:1407
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff821473d0-ffffffff82147470: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82229bf0)
Location: mm/memory_hotplug.c:1589
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_enable_device
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff82229bf0-ffffffff82229c90: __add_memory (STB_GLOBAL)
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
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9d460)
Location: mm/memory_hotplug.c:1122
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
```
**Symbols:**

```
ffff800010d9d460-ffff800010d9d554: __add_memory (STB_GLOBAL)
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
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c000000000430460)
Location: mm/memory_hotplug.c:1122
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
c000000000430460-c0000000004305f0: __add_memory (STB_GLOBAL)
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
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a684e0)
Location: mm/memory_hotplug.c:1122
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81a684e0-ffffffff81a685ab: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24fa0)
Location: mm/memory_hotplug.c:1122
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81a24fa0-ffffffff81a2506b: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad48f0)
Location: mm/memory_hotplug.c:1122
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81ad48f0-ffffffff81ad49bb: __add_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __add_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0dd0)
Location: mm/memory_hotplug.c:1122
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/base/memory.c:probe_store
```
**Symbols:**

```
ffffffff81ae0dd0-ffffffff81ae0e9b: __add_memory (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>mhp_t mhp_flags</code>
</li>
</ul>
</details>
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
