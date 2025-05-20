# Function: <code>efi_set_executable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff81f79e72)
Location: arch/x86/platform/efi/efi.c:537
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
```
**Symbols:**

```
ffffffff81f79e72-ffffffff81f79eb6: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff81fa267e)
Location: arch/x86/platform/efi/efi.c:518
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
```
**Symbols:**

```
ffffffff81fa267e-ffffffff81fa26c2: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff81fddfe9)
Location: arch/x86/platform/efi/efi.c:550
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
```
**Symbols:**

```
ffffffff81fddfe9-ffffffff81fde02d: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff820beddb)
Location: arch/x86/platform/efi/efi.c:546
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
```
**Symbols:**

```
ffffffff820beddb-ffffffff820bee25: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff826c6f00)
Location: arch/x86/platform/efi/efi.c:547
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
```
**Symbols:**

```
ffffffff826c6f00-ffffffff826c6f4a: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff826f1008)
Location: arch/x86/platform/efi/efi.c:547
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff826f1008-ffffffff826f1052: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828a7da0)
Location: arch/x86/platform/efi/efi.c:546
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff828a7da0-ffffffff828a7dea: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c04b5)
Location: arch/x86/platform/efi/efi.c:548
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff828c04b5-ffffffff828c0500: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c6957)
Location: arch/x86/platform/efi/efi.c:572
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff828c6957-ffffffff828c69a2: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff82cea0f9)
Location: arch/x86/platform/efi/efi.c:501
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/uv/bios_uv.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff82cea0f9-ffffffff82cea166: efi_set_executable (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828b18ef)
Location: arch/x86/platform/efi/efi.c:572
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff828b18ef-ffffffff828b193a: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828a9a74)
Location: arch/x86/platform/efi/efi.c:572
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff828a9a74-ffffffff828a9abf: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c47ee)
Location: arch/x86/platform/efi/efi.c:572
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff828c47ee-ffffffff828c4839: efi_set_executable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void efi_set_executable(efi_memory_desc_t *md, bool executable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff828c7994)
Location: arch/x86/platform/efi/efi.c:572
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:runtime_code_page_mkexec
  - arch/x86/platform/efi/efi_64.c:early_code_mapping_set_exec
```
**Symbols:**

```
ffffffff828c7994-ffffffff828c79df: efi_set_executable (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
