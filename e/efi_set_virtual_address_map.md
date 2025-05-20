# Function: <code>efi_set_virtual_address_map</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceb0c6)
Location: arch/x86/platform/efi/efi_64.c:845
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff82ceb0c6-ffffffff82ceb1c1: efi_set_virtual_address_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8940)
Location: arch/x86/platform/efi/efi_64.c:817
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff82fd8940-ffffffff82fd89f2: efi_set_virtual_address_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff831e3330)
Location: arch/x86/platform/efi/efi_64.c:820
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff831e3330-ffffffff831e33d8: efi_set_virtual_address_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6cd3)
Location: arch/x86/platform/efi/efi_64.c:820
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff832c6cd3-ffffffff832c6d7b: efi_set_virtual_address_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff83479aa6)
Location: arch/x86/platform/efi/efi_64.c:821
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff83479aa6-ffffffff83479b61: efi_set_virtual_address_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3e10)
Location: arch/x86/platform/efi/efi_64.c:829
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff83ea3e10-ffffffff83ea3f1f: efi_set_virtual_address_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff836c80c0)
Location: arch/x86/platform/efi/efi_64.c:835
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff836c80c0-ffffffff836c81f2: efi_set_virtual_address_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
efi_status_t efi_set_virtual_address_map(long unsigned int memory_map_size, long unsigned int descriptor_size, u32 descriptor_version, efi_memory_desc_t *virtual_map, long unsigned int systab_phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8cc0)
Location: arch/x86/platform/efi/efi_64.c:850
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
```
**Symbols:**

```
ffffffff838f8cc0-ffffffff838f8df2: efi_set_virtual_address_map (STB_GLOBAL)
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
