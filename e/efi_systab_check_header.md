# Function: <code>efi_systab_check_header</code>

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
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr, int min_major_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82d29cf3)
Location: drivers/firmware/efi/efi.c:658
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_systab_init
```
**Symbols:**

```
ffffffff82d29cf3-ffffffff82d29d48: efi_systab_check_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr, int min_major_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83018418)
Location: drivers/firmware/efi/efi.c:665
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_systab_init
```
**Symbols:**

```
ffffffff83018418-ffffffff8301846d: efi_systab_check_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr, int min_major_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff832232f0)
Location: drivers/firmware/efi/efi.c:665
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff832232f0-ffffffff83223345: efi_systab_check_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr, int min_major_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8330d071)
Location: drivers/firmware/efi/efi.c:665
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff8330d071-ffffffff8330d0c6: efi_systab_check_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr, int min_major_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff834c6b39)
Location: drivers/firmware/efi/efi.c:679
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_init
```
**Symbols:**

```
ffffffff834c6b39-ffffffff834c6b95: efi_systab_check_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr, int min_major_version);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83f07c80)
Location: drivers/firmware/efi/efi.c:703
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_systab_init
```
**Symbols:**

```
ffffffff83f07c80-ffffffff83f07ce8: efi_systab_check_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8372dda0)
Location: drivers/firmware/efi/efi.c:771
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_systab_init
```
**Symbols:**

```
ffffffff8372dda0-ffffffff8372ddda: efi_systab_check_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_systab_check_header(const efi_table_hdr_t *systab_hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff839621a0)
Location: drivers/firmware/efi/efi.c:819
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi.c:efi_systab_init
```
**Symbols:**

```
ffffffff839621a0-ffffffff839621da: efi_systab_check_header (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int min_major_version</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
