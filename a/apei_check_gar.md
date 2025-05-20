# Function: <code>apei_check_gar</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff814b2d00)
Location: drivers/acpi/apei/apei-base.c:577
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_write
```
**Symbols:**

```
ffffffff814b2d00-ffffffff814b2e0d: apei_check_gar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81502620)
Location: drivers/acpi/apei/apei-base.c:579
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff81502620-ffffffff8150272d: apei_check_gar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81526810)
Location: drivers/acpi/apei/apei-base.c:579
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff81526810-ffffffff8152691d: apei_check_gar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81539720)
Location: drivers/acpi/apei/apei-base.c:579
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff81539720-ffffffff81539836: apei_check_gar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8159c280)
Location: drivers/acpi/apei/apei-base.c:579
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff8159c280-ffffffff8159c396: apei_check_gar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:579
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff815d3fa0-ffffffff815d4041: apei_check_gar (STB_LOCAL)
ffffffff815d4d6e-ffffffff815d4de9: apei_check_gar.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:579
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff815ed750-ffffffff815ed7f1: apei_check_gar (STB_LOCAL)
ffffffff815ee51e-ffffffff815ee599: apei_check_gar.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff8161f500-ffffffff8161f5a5: apei_check_gar (STB_LOCAL)
ffffffff816202b0-ffffffff8162032b: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff81640fe0-ffffffff81641085: apei_check_gar (STB_LOCAL)
ffffffff81641d90-ffffffff81641e0b: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff816edfa0-ffffffff816ee047: apei_check_gar (STB_LOCAL)
ffffffff816ef13d-ffffffff816ef1b8: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff8170b5b0-ffffffff8170b657: apei_check_gar (STB_LOCAL)
ffffffff81c0334c-ffffffff81c033c7: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff816ecbf0-ffffffff816ecc97: apei_check_gar (STB_LOCAL)
ffffffff81bf4d3d-ffffffff81bf4db8: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81766d30-ffffffff81766dd7: apei_check_gar (STB_LOCAL)
ffffffff81cf2097-ffffffff81cf2112: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff8189b380-ffffffff8189b439: apei_check_gar (STB_LOCAL)
ffffffff81eba10a-ffffffff81eba16d: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff819e39f0)
Location: drivers/acpi/apei/apei-base.c:568
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff819e39f0-ffffffff819e3b1d: apei_check_gar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a2c010)
Location: drivers/acpi/apei/apei-base.c:568
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81a2c010-ffffffff81a2c13d: apei_check_gar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a771e0)
Location: drivers/acpi/apei/apei-base.c:568
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_exec_pre_map_gars
```
**Symbols:**

```
ffffffff81a771e0-ffffffff81a7730d: apei_check_gar (STB_LOCAL)
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
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffff8000107abd20)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffff8000107abd20-ffff8000107abe54: apei_check_gar (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff815fd3f0-ffffffff815fd495: apei_check_gar (STB_LOCAL)
ffffffff815fe1a0-ffffffff815fe21b: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff81634e20-ffffffff81634ec5: apei_check_gar (STB_LOCAL)
ffffffff81635bd0-ffffffff81635c4b: apei_check_gar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int apei_check_gar(struct acpi_generic_address *reg, u64 *paddr, u32 *access_bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/apei-base.c (0)
Location: drivers/acpi/apei/apei-base.c:571
Inline: False
Direct callers:
  - drivers/acpi/apei/apei-base.c:collect_res_callback
  - drivers/acpi/apei/apei-base.c:apei_write
  - drivers/acpi/apei/apei-base.c:apei_read
  - drivers/acpi/apei/apei-base.c:apei_map_generic_address
```
**Symbols:**

```
ffffffff8164f130-ffffffff8164f1d5: apei_check_gar (STB_LOCAL)
ffffffff8164fee0-ffffffff8164ff5b: apei_check_gar.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
