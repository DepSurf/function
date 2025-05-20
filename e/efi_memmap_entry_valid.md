# Function: <code>efi_memmap_entry_valid</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff81fdde49)
Location: arch/x86/platform/efi/efi.c:217
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff820bec38)
Location: arch/x86/platform/efi/efi.c:218
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff826c6d5d)
Location: arch/x86/platform/efi/efi.c:219
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff826f0e59)
Location: arch/x86/platform/efi/efi.c:219
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828a7bf4)
Location: arch/x86/platform/efi/efi.c:218
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c02fe)
Location: arch/x86/platform/efi/efi.c:220
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c67a0)
Location: arch/x86/platform/efi/efi.c:243
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82ce9a0c)
Location: arch/x86/platform/efi/efi.c:258
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82ce9a0c-ffffffff82ce9b28: efi_memmap_entry_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82fd7477)
Location: arch/x86/platform/efi/efi.c:260
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff82fd7477-ffffffff82fd7593: efi_memmap_entry_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff831e1e5e)
Location: arch/x86/platform/efi/efi.c:260
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff831e1e5e-ffffffff831e1f7a: efi_memmap_entry_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff832c576c)
Location: arch/x86/platform/efi/efi.c:260
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff832c576c-ffffffff832c58a2: efi_memmap_entry_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff83478441)
Location: arch/x86/platform/efi/efi.c:263
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff83478441-ffffffff834785fa: efi_memmap_entry_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff83ea2490)
Location: arch/x86/platform/efi/efi.c:242
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff83ea2490-ffffffff83ea2685: efi_memmap_entry_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff836c66e0)
Location: arch/x86/platform/efi/efi.c:245
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff836c66e0-ffffffff836c68d5: efi_memmap_entry_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool efi_memmap_entry_valid(const efi_memory_desc_t *md, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff838f72e0)
Location: arch/x86/platform/efi/efi.c:245
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
**Symbols:**

```
ffffffff838f72e0-ffffffff838f74d5: efi_memmap_entry_valid (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828b1738)
Location: arch/x86/platform/efi/efi.c:243
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828a98bd)
Location: arch/x86/platform/efi/efi.c:243
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c4637)
Location: arch/x86/platform/efi/efi.c:243
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c77dd)
Location: arch/x86/platform/efi/efi.c:243
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_clean_memmap
```
</details>
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
