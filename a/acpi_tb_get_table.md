# Function: <code>acpi_tb_get_table</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff8151799a)
Location: drivers/acpi/acpica/tbutils.c:402
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff8151799a-ffffffff815179f9: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff815281b5)
Location: drivers/acpi/acpica/tbutils.c:402
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff815281b5-ffffffff8152821a: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff8157fa22)
Location: drivers/acpi/acpica/tbutils.c:402
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff8157fa22-ffffffff8157faed: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff815b6c1a)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff815b6c1a-ffffffff815b6ce5: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff815cffd7)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff815cffd7-ffffffff815d00a2: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff81601863)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff81601863-ffffffff8160192e: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff81622d0e)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff81622d0e-ffffffff81622dd8: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff816cf356)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff816cf356-ffffffff816cf420: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff816ed356)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff816ed356-ffffffff816ed420: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff816cf212)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff816cf212-ffffffff816cf2dc: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff81746882)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff81746882-ffffffff8174694c: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff818787e0)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff818787e0-ffffffff818788b9: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff819bab80)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff819bab80-ffffffff819bac68: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff81a01d20)
Location: drivers/acpi/acpica/tbutils.c:369
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff81a01d20-ffffffff81a01e08: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff81a4cba0)
Location: drivers/acpi/acpica/tbutils.c:369
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff81a4cba0-ffffffff81a4cc88: acpi_tb_get_table (STB_GLOBAL)
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
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffff800010798278)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffff800010798278-ffff800010798308: acpi_tb_get_table (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff815fcded)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff815fcded-ffffffff815fce51: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff815e8313)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
  - drivers/acpi/acpica/tbxface.c:acpi_get_table_by_index
```
**Symbols:**

```
ffffffff815e8313-ffffffff815e8377: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff81616fee)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff81616fee-ffffffff816170b8: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_tb_get_table(struct acpi_table_desc *table_desc, struct acpi_table_header **out_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbutils.c (ffffffff81630e9e)
Location: drivers/acpi/acpica/tbutils.c:368
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbfadt.c:acpi_tb_parse_fadt
```
**Symbols:**

```
ffffffff81630e9e-ffffffff81630f68: acpi_tb_get_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
