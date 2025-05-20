# Function: <code>add_bootloader_randomness</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bef10)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff816bef10-ffffffff816bef29: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817728f0)
Location: drivers/char/random.c:2323
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff817728f0-ffffffff81772909: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178d940)
Location: drivers/char/random.c:2322
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff8178d940-ffffffff8178d959: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817712b0)
Location: drivers/char/random.c:2298
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff817712b0-ffffffff817712c9: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f6e60)
Location: drivers/char/random.c:2327
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff817f6e60-ffffffff817f6e79: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff834b3f63)
Location: drivers/char/random.c:864
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff834b3f63-ffffffff834b3fc1: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff83eeee10)
Location: drivers/char/random.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_setup_data
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff83eeee10-ffffffff83eeeea8: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff83714a50)
Location: drivers/char/random.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_setup_data
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff83714a50-ffffffff83714ae8: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff839484b0)
Location: drivers/char/random.c:952
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:parse_setup_data
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff839484b0-ffffffff83948548: add_bootloader_randomness (STB_GLOBAL)
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
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b0a18)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/of/fdt.c:early_init_dt_scan_chosen
```
**Symbols:**

```
ffff8000108b0a18-ffff8000108b0a50: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09ab64c)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/of/fdt.c:early_init_dt_scan_chosen
```
**Symbols:**

```
c09ab64c-c09ab66c: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947c40)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen
```
**Symbols:**

```
c000000000947c40-c000000000947c58: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000563876)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/of/fdt.c:early_init_dt_scan_chosen
```
**Symbols:**

```
ffffffe000563876-ffffffe0005638b4: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81682950)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff81682950-ffffffff81682960: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662600)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff81662600-ffffffff81662619: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b2d50)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff816b2d50-ffffffff816b2d69: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_bootloader_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd2b0)
Location: drivers/char/random.c:2515
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff816cd2b0-ffffffff816cd2c9: add_bootloader_randomness (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
