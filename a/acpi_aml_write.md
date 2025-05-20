# Function: <code>acpi_aml_write</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159b9b0)
Location: drivers/acpi/acpi_dbg.c:679
Inline: True
```
**Symbols:**

```
ffffffff8159b9b0-ffffffff8159bc0e: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815d38c0)
Location: drivers/acpi/acpi_dbg.c:679
Inline: True
```
**Symbols:**

```
ffffffff815d38c0-ffffffff815d3b26: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815ed070)
Location: drivers/acpi/acpi_dbg.c:679
Inline: True
```
**Symbols:**

```
ffffffff815ed070-ffffffff815ed2d6: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8161ee30)
Location: drivers/acpi/acpi_dbg.c:676
Inline: True
```
**Symbols:**

```
ffffffff8161ee30-ffffffff8161f087: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816408e0)
Location: drivers/acpi/acpi_dbg.c:676
Inline: True
```
**Symbols:**

```
ffffffff816408e0-ffffffff81640b57: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ed210)
Location: drivers/acpi/acpi_dbg.c:676
Inline: True
```
**Symbols:**

```
ffffffff816ed210-ffffffff816ed381: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff816ed390-ffffffff816ed3cd: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8170a800)
Location: drivers/acpi/acpi_dbg.c:669
Inline: True
```
**Symbols:**

```
ffffffff8170a800-ffffffff8170a9c0: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff8170a9c0-ffffffff8170a9d8: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ebdb0)
Location: drivers/acpi/acpi_dbg.c:669
Inline: True
```
**Symbols:**

```
ffffffff816ebdb0-ffffffff816ec033: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff816ec040-ffffffff816ec077: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81765ed0)
Location: drivers/acpi/acpi_dbg.c:669
Inline: True
```
**Symbols:**

```
ffffffff81765ed0-ffffffff81766153: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff81766160-ffffffff81766197: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8189aed0)
Location: drivers/acpi/acpi_dbg.c:669
Inline: True
```
**Symbols:**

```
ffffffff8189aed0-ffffffff8189b1c9: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff8189b1d0-ffffffff8189b224: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff819e34b0)
Location: drivers/acpi/acpi_dbg.c:669
Inline: True
```
**Symbols:**

```
ffffffff819e34b0-ffffffff819e37aa: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff819e37c0-ffffffff819e3814: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a2bac0)
Location: drivers/acpi/acpi_dbg.c:669
Inline: True
```
**Symbols:**

```
ffffffff81a2bac0-ffffffff81a2bdb3: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff81a2bdd0-ffffffff81a2be34: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a76c90)
Location: drivers/acpi/acpi_dbg.c:669
Inline: True
```
**Symbols:**

```
ffffffff81a76c90-ffffffff81a76f83: acpi_aml_write.part.0 (STB_LOCAL)
ffffffff81a76fa0-ffffffff81a77004: acpi_aml_write (STB_LOCAL)
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
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81634720)
Location: drivers/acpi/acpi_dbg.c:676
Inline: True
```
**Symbols:**

```
ffffffff81634720-ffffffff81634997: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8164ea40)
Location: drivers/acpi/acpi_dbg.c:676
Inline: True
```
**Symbols:**

```
ffffffff8164ea40-ffffffff8164ecb2: acpi_aml_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
