# Function: <code>match_config_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int match_config_table(efi_guid_t *guid, long unsigned int table, efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81fb63bd)
Location: drivers/firmware/efi/efi.c:373
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff81fb63bd-ffffffff81fb64da: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int match_config_table(efi_guid_t *guid, long unsigned int table, efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81fe39d0)
Location: drivers/firmware/efi/efi.c:442
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff81fe39d0-ffffffff81fe3b2c: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int match_config_table(efi_guid_t *guid, long unsigned int table, efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8202179f)
Location: drivers/firmware/efi/efi.c:451
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff8202179f-ffffffff820218fb: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82104bf4)
Location: drivers/firmware/efi/efi.c:450
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff821044d5-ffffffff82104603: match_config_table.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8270e2a3)
Location: drivers/firmware/efi/efi.c:470
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff8270db84-ffffffff8270dcb2: match_config_table.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff827380e0)
Location: drivers/firmware/efi/efi.c:482
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff827380e0-ffffffff82738200: match_config_table.isra.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828f20be)
Location: drivers/firmware/efi/efi.c:493
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff828f20be-ffffffff828f21de: match_config_table.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8290d725)
Location: drivers/firmware/efi/efi.c:494
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff8290d725-ffffffff8290d840: match_config_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82916dea)
Location: drivers/firmware/efi/efi.c:484
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff82916dea-ffffffff82916f05: match_config_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82d29332)
Location: drivers/firmware/efi/efi.c:526
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff82d29332-ffffffff82d29454: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83017a4a)
Location: drivers/firmware/efi/efi.c:533
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff83017a4a-ffffffff83017b6c: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83222922)
Location: drivers/firmware/efi/efi.c:533
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff83222922-ffffffff83222a44: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8330c686)
Location: drivers/firmware/efi/efi.c:533
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff8330c686-ffffffff8330c7a8: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff834c5f68)
Location: drivers/firmware/efi/efi.c:547
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff834c5f68-ffffffff834c6085: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83f06b80)
Location: drivers/firmware/efi/efi.c:559
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff83f06b80-ffffffff83f06c77: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8372cbb0)
Location: drivers/firmware/efi/efi.c:601
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff8372cbb0-ffffffff8372cccf: match_config_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int match_config_table(const efi_guid_t *guid, long unsigned int table, const efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83960f90)
Location: drivers/firmware/efi/efi.c:623
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff83960f90-ffffffff839610af: match_config_table (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff8000114a54b4)
Location: drivers/firmware/efi/efi.c:484
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffff8000114a54b4-ffff8000114a55ac: match_config_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int match_config_table(efi_guid_t *guid, long unsigned int table, efi_config_table_type_t *table_types);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c15a7790)
Location: drivers/firmware/efi/efi.c:484
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
c15a7790-c15a7894: match_config_table (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828fc1f0)
Location: drivers/firmware/efi/efi.c:484
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff828fc1f0-ffffffff828fc30b: match_config_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828f3a8c)
Location: drivers/firmware/efi/efi.c:484
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff828f3a8c-ffffffff828f3ba7: match_config_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8291141f)
Location: drivers/firmware/efi/efi.c:484
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff8291141f-ffffffff8291153a: match_config_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82917e4c)
Location: drivers/firmware/efi/efi.c:484
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
```
**Symbols:**

```
ffffffff82917e4c-ffffffff82917f67: match_config_table.isra.0 (STB_LOCAL)
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
</ul>
