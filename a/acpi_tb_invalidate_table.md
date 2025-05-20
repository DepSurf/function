# Function: <code>acpi_tb_invalidate_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff814a44e2)
Location: drivers/acpi/acpica/tbdata.c:306
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
```
**Symbols:**

```
ffffffff814a44e2-ffffffff814a450f: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff814f3826)
Location: drivers/acpi/acpica/tbdata.c:306
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
```
**Symbols:**

```
ffffffff814f3826-ffffffff814f3853: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81516374)
Location: drivers/acpi/acpica/tbdata.c:307
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff81516374-ffffffff815163a1: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81526bdc)
Location: drivers/acpi/acpica/tbdata.c:307
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff81526bdc-ffffffff81526c09: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8157dd67)
Location: drivers/acpi/acpica/tbdata.c:359
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff8157dd67-ffffffff8157dde8: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815b4f46)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff815b4f46-ffffffff815b4fc7: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815ce302)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff815ce302-ffffffff815ce383: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815ffb6c)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff815ffb6c-ffffffff815ffbed: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81621016)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff81621016-ffffffff81621097: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd76d)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff816cd76d-ffffffff816cd7ee: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816eb773)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff816eb773-ffffffff816eb7f4: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816cd653)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff816cd653-ffffffff816cd6d4: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81744b23)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff81744b23-ffffffff81744ba4: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81876841)
Location: drivers/acpi/acpica/tbdata.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff81876841-ffffffff818768d8: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819b8420)
Location: drivers/acpi/acpica/tbdata.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff819b8420-ffffffff819b84cb: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff819ff580)
Location: drivers/acpi/acpica/tbdata.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff819ff580-ffffffff819ff62b: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff81a4a400)
Location: drivers/acpi/acpica/tbdata.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff81a4a400-ffffffff81a4a4ab: acpi_tb_invalidate_table (STB_GLOBAL)
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
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffff800010796960)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffff800010796960-ffff80001079699c: acpi_tb_invalidate_table (STB_GLOBAL)
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
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815fb77f)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff815fb77f-ffffffff815fb7ac: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff815e6caf)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: False
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff815e6caf-ffffffff815e6cdc: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff816152f6)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff816152f6-ffffffff81615377: acpi_tb_invalidate_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_tb_invalidate_table(struct acpi_table_desc *table_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbdata.c (ffffffff8162f1a6)
Location: drivers/acpi/acpica/tbdata.c:325
Inline: True
Direct callers:
  - drivers/acpi/acpica/tbdata.c:acpi_tb_verify_temp_table
  - drivers/acpi/acpica/tbdata.c:acpi_tb_release_temp_table
  - drivers/acpi/acpica/tbutils.c:acpi_tb_put_table
```
**Symbols:**

```
ffffffff8162f1a6-ffffffff8162f227: acpi_tb_invalidate_table (STB_GLOBAL)
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
