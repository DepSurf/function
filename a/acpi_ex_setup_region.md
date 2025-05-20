# Function: <code>acpi_ex_setup_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff814955dc)
Location: drivers/acpi/acpica/exfldio.c:83
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff814e45e8)
Location: drivers/acpi/acpica/exfldio.c:83
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81506e3c)
Location: drivers/acpi/acpica/exfldio.c:83
Inline: True
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
In drivers/acpi/acpica/exfldio.c (ffffffff8151742e)
Location: drivers/acpi/acpica/exfldio.c:83
Inline: True
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
In drivers/acpi/acpica/exfldio.c (ffffffff81564057)
Location: drivers/acpi/acpica/exfldio.c:83
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
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
In drivers/acpi/acpica/exfldio.c (ffffffff8159ad9e)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
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
In drivers/acpi/acpica/exfldio.c (ffffffff815b3290)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
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
In drivers/acpi/acpica/exfldio.c (ffffffff815e4dab)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
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
In drivers/acpi/acpica/exfldio.c (ffffffff81606140)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff816b235a)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff816b235a-ffffffff816b261c: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff816cfc96)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff816cfc96-ffffffff816cff58: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff816b1c4e)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff816b1c4e-ffffffff816b1f10: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81728ad7)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff81728ad7-ffffffff81728d99: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff818592c3)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff818592c3-ffffffff8185959c: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81994e60)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff81994e60-ffffffff81995182: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff819dba70)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff819dba70-ffffffff819dbda9: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_setup_region(union acpi_operand_object *obj_desc, u32 field_datum_byte_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff81a26760)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: False
Direct callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
```
**Symbols:**

```
ffffffff81a26760-ffffffff81a26a99: acpi_ex_setup_region (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffff8000107851ac)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exfldio.c (ffffffff815eb1e6)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
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
In drivers/acpi/acpica/exfldio.c (ffffffff815d6804)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
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
In drivers/acpi/acpica/exfldio.c (ffffffff815fa420)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
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
In drivers/acpi/acpica/exfldio.c (ffffffff816142d0)
Location: drivers/acpi/acpica/exfldio.c:49
Inline: True
Inline callers:
  - drivers/acpi/acpica/exfldio.c:acpi_ex_access_region
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
