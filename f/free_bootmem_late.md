# Function: <code>free_bootmem_late</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_bootmem_late(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8acc6)
Location: mm/nobootmem.c:79
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff81f8acc6-ffffffff81f8ad1f: free_bootmem_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_bootmem_late(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb4905)
Location: mm/nobootmem.c:80
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff81fb4905-ffffffff81fb495e: free_bootmem_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_bootmem_late(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff12f1)
Location: mm/nobootmem.c:83
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff81ff12f1-ffffffff81ff1344: free_bootmem_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_bootmem_late(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d3717)
Location: mm/nobootmem.c:83
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff820d3717-ffffffff820d376f: free_bootmem_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_bootmem_late(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc137)
Location: mm/nobootmem.c:84
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
```
**Symbols:**

```
ffffffff826dc137-ffffffff826dc18f: free_bootmem_late (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_bootmem_late(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff82706600)
Location: mm/nobootmem.c:84
Inline: False
Direct callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - drivers/firmware/efi/apple-properties.c:map_properties
```
**Symbols:**

```
ffffffff82706600-ffffffff8270664d: free_bootmem_late (STB_GLOBAL)
```
</details>
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
</ul>
