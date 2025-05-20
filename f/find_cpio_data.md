# Function: <code>find_cpio_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff813e93f0)
Location: lib/earlycpio.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
**Symbols:**

```
ffffffff813e93f0-ffffffff813e96d7: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff8142f5f0)
Location: lib/earlycpio.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff8142f5f0-ffffffff8142f8d8: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff8144b820)
Location: lib/earlycpio.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff8144b820-ffffffff8144bb08: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff818ebfd0)
Location: lib/earlycpio.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff818ebfd0-ffffffff818ec2c3: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff81971fc0)
Location: lib/earlycpio.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81971fc0-ffffffff8197229f: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff819ce693-ffffffff819ce6d6: find_cpio_data.cold.0 (STB_LOCAL)
ffffffff819ce3c0-ffffffff819ce693: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81a07b53-ffffffff81a07b96: find_cpio_data.cold.0 (STB_LOCAL)
ffffffff81a07880-ffffffff81a07b53: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81a774cd-ffffffff81a77510: find_cpio_data.cold (STB_LOCAL)
ffffffff81a77210-ffffffff81a774cd: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81aae8bd-ffffffff81aae900: find_cpio_data.cold (STB_LOCAL)
ffffffff81aae600-ffffffff81aae8bd: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff815e8606-ffffffff815e8649: find_cpio_data.cold (STB_LOCAL)
ffffffff815e8350-ffffffff815e8606: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81bf4a4e-ffffffff81bf4a91: find_cpio_data.cold (STB_LOCAL)
ffffffff8160d440-ffffffff8160d6f6: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81be6957-ffffffff81be699a: find_cpio_data.cold (STB_LOCAL)
ffffffff815f0ba0-ffffffff815f0e3a: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81cdf1c7-ffffffff81cdf20a: find_cpio_data.cold (STB_LOCAL)
ffffffff8165dce0-ffffffff8165df7a: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81ea59a9-ffffffff81ea59de: find_cpio_data.cold (STB_LOCAL)
ffffffff81777330-ffffffff817775fe: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff8201feb0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff8201feb0-ffffffff820201e8: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff8209fdc0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff8209fdc0-ffffffff820a00f8: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffffffff82177d90)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff82177d90-ffffffff821780c8: find_cpio_data (STB_GLOBAL)
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
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/earlycpio.c (ffff800010d84c40)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffff800010d84c40-ffff800010d84ed8: find_cpio_data (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81a4d70d-ffffffff81a4d750: find_cpio_data.cold (STB_LOCAL)
ffffffff81a4d450-ffffffff81a4d70d: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
```
**Symbols:**

```
ffffffff81a0a81d-ffffffff81a0a860: find_cpio_data.cold (STB_LOCAL)
ffffffff81a0a560-ffffffff81a0a81d: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81ab9afd-ffffffff81ab9b40: find_cpio_data.cold (STB_LOCAL)
ffffffff81ab9840-ffffffff81ab9afd: find_cpio_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_cpio_data(const char *path, void *data, size_t len, long int *nextoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/earlycpio.c (0)
Location: lib/earlycpio.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:find_microcode_in_initrd
  - drivers/acpi/tables.c:acpi_table_upgrade
```
**Symbols:**

```
ffffffff81ac5f4d-ffffffff81ac5f90: find_cpio_data.cold (STB_LOCAL)
ffffffff81ac5c90-ffffffff81ac5f4d: find_cpio_data (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
