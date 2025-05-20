# Function: <code>acpi_table_attr_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_table_attr_init(struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81489a90)
Location: drivers/acpi/sysfs.c:347
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
**Symbols:**

```
ffffffff81489a90-ffffffff81489b8e: acpi_table_attr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_table_attr_init(struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814d87b1)
Location: drivers/acpi/sysfs.c:347
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff814d87b1-ffffffff814d88af: acpi_table_attr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814fae99)
Location: drivers/acpi/sysfs.c:346
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff814fae99-ffffffff814fafbb: acpi_table_attr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8150a4e0)
Location: drivers/acpi/sysfs.c:349
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff8150a4e0-ffffffff8150a619: acpi_table_attr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8154cda0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff8154cda0-ffffffff8154ced9: acpi_table_attr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff81583510-ffffffff81583632: acpi_table_attr_init (STB_LOCAL)
ffffffff81584385-ffffffff8158439f: acpi_table_attr_init.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff8159b640-ffffffff8159b762: acpi_table_attr_init (STB_LOCAL)
ffffffff8159c4b5-ffffffff8159c4cf: acpi_table_attr_init.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff815cccb0-ffffffff815ccde5: acpi_table_attr_init (STB_LOCAL)
ffffffff815cdb36-ffffffff815cdb51: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff815edf30-ffffffff815ee065: acpi_table_attr_init (STB_LOCAL)
ffffffff815eedb6-ffffffff815eedd1: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff81699f90-ffffffff8169a0c5: acpi_table_attr_init (STB_LOCAL)
ffffffff8169ad87-ffffffff8169ada2: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff816b7000-ffffffff816b7144: acpi_table_attr_init (STB_LOCAL)
ffffffff81c024ca-ffffffff81c024f1: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:344
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff816990c0-ffffffff81699204: acpi_table_attr_init (STB_LOCAL)
ffffffff81bf3cc3-ffffffff81bf3cea: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:341
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff8170ef50-ffffffff8170f094: acpi_table_attr_init (STB_LOCAL)
ffffffff81cf0a03-ffffffff81cf0a2a: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:341
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff8183d9e0-ffffffff8183db27: acpi_table_attr_init (STB_LOCAL)
ffffffff81eb885b-ffffffff81eb8881: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff819735f0)
Location: drivers/acpi/sysfs.c:342
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff819735f0-ffffffff8197375c: acpi_table_attr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff819b9b90)
Location: drivers/acpi/sysfs.c:342
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff819b9b90-ffffffff819b9d77: acpi_table_attr_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81a041d0)
Location: drivers/acpi/sysfs.c:342
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff81a041d0-ffffffff81a043b7: acpi_table_attr_init (STB_LOCAL)
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
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffff800010779448)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffff800010779448-ffff8000107795cc: acpi_table_attr_init (STB_LOCAL)
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
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff815dcc80-ffffffff815dcdb5: acpi_table_attr_init (STB_LOCAL)
ffffffff815dda51-ffffffff815dda6c: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff815c82c0-ffffffff815c83f5: acpi_table_attr_init (STB_LOCAL)
ffffffff815c9091-ffffffff815c90ac: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff815e2210-ffffffff815e2345: acpi_table_attr_init (STB_LOCAL)
ffffffff815e3096-ffffffff815e30b1: acpi_table_attr_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_table_attr_init(struct kobject *tables_obj, struct acpi_table_attr *table_attr, struct acpi_table_header *table_header);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:362
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
**Symbols:**

```
ffffffff815fc0d0-ffffffff815fc205: acpi_table_attr_init (STB_LOCAL)
ffffffff815fcf56-ffffffff815fcf71: acpi_table_attr_init.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *tables_obj</code>
</li>
<li>
<b>Param reordered. </b>
<code>table_attr, table_header</code> ➡️ <code>tables_obj, table_attr, table_header</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
