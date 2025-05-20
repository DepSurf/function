# Function: <code>acpi_os_physical_table_override</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479f1d)
Location: drivers/acpi/osl.c:751
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff81479f1d-ffffffff81479f37: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff814c7c87)
Location: drivers/acpi/tables.c:719
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff814c7c87-ffffffff814c7dff: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff814e9b97)
Location: drivers/acpi/tables.c:718
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff814e9b97-ffffffff814e9d0f: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff814f5840)
Location: drivers/acpi/tables.c:707
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff814f5840-ffffffff814f59a8: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff815360d0)
Location: drivers/acpi/tables.c:707
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff815360d0-ffffffff81536238: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:713
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff8156bdc2-ffffffff8156be02: acpi_os_physical_table_override.cold.1 (STB_LOCAL)
ffffffff8156bb00-ffffffff8156bc22: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:712
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff81583988-ffffffff815839c8: acpi_os_physical_table_override.cold.1 (STB_LOCAL)
ffffffff815836d0-ffffffff815837f2: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:759
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff815b455f-ffffffff815b45a0: acpi_os_physical_table_override.cold (STB_LOCAL)
ffffffff815b42d0-ffffffff815b4403: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff815d578f-ffffffff815d57d0: acpi_os_physical_table_override.cold (STB_LOCAL)
ffffffff815d5510-ffffffff815d563a: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff8167f2d0)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff8167f2d0-ffffffff8167f2e0: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff8169df60)
Location: drivers/acpi/tables.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff8169df60-ffffffff8169df70: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81680cb0)
Location: drivers/acpi/tables.c:749
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff81680cb0-ffffffff81680cc0: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff816f5d70)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff816f5d70-ffffffff816f5d80: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81822b10)
Location: drivers/acpi/tables.c:805
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff81822b10-ffffffff81822b2a: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81953a10)
Location: drivers/acpi/tables.c:815
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff81953a10-ffffffff81953a2a: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff81999e10)
Location: drivers/acpi/tables.c:826
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff81999e10-ffffffff81999e2a: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff819e2290)
Location: drivers/acpi/tables.c:654
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff819e2290-ffffffff819e22aa: acpi_os_physical_table_override (STB_GLOBAL)
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
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffff800010762b38)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffff800010762b38-ffff800010762d1c: acpi_os_physical_table_override (STB_GLOBAL)
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
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff815c94df-ffffffff815c9520: acpi_os_physical_table_override.cold (STB_LOCAL)
ffffffff815c9260-ffffffff815c938a: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/tables.c (ffffffff815b2440)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff815b2440-ffffffff815b245a: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff815c9a6f-ffffffff815c9ab0: acpi_os_physical_table_override.cold (STB_LOCAL)
ffffffff815c97f0-ffffffff815c991a: acpi_os_physical_table_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_physical_table_override(struct acpi_table_header *existing_table, acpi_physical_address *address, u32 *table_length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/tables.c (0)
Location: drivers/acpi/tables.c:760
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbinstal.c:acpi_tb_override_table
```
**Symbols:**

```
ffffffff815e38cf-ffffffff815e3910: acpi_os_physical_table_override.cold (STB_LOCAL)
ffffffff815e3650-ffffffff815e377a: acpi_os_physical_table_override (STB_GLOBAL)
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
