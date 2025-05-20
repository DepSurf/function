# Function: <code>acpi_aml_read</code>

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
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159be30)
Location: drivers/acpi/acpi_dbg.c:609
Inline: True
```
**Symbols:**

```
ffffffff8159be30-ffffffff8159c064: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815d3b30)
Location: drivers/acpi/acpi_dbg.c:609
Inline: True
```
**Symbols:**

```
ffffffff815d3b30-ffffffff815d3d6f: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815ed2e0)
Location: drivers/acpi/acpi_dbg.c:609
Inline: True
```
**Symbols:**

```
ffffffff815ed2e0-ffffffff815ed51f: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8161f090)
Location: drivers/acpi/acpi_dbg.c:606
Inline: True
```
**Symbols:**

```
ffffffff8161f090-ffffffff8161f2c8: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81640b60)
Location: drivers/acpi/acpi_dbg.c:606
Inline: True
```
**Symbols:**

```
ffffffff81640b60-ffffffff81640da8: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816edce0)
Location: drivers/acpi/acpi_dbg.c:606
Inline: True
```
**Symbols:**

```
ffffffff816edce0-ffffffff816ede0f: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff816ede10-ffffffff816ede4d: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8170b2f0)
Location: drivers/acpi/acpi_dbg.c:599
Inline: True
```
**Symbols:**

```
ffffffff8170b2f0-ffffffff8170b46e: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff8170b470-ffffffff8170b488: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ec840)
Location: drivers/acpi/acpi_dbg.c:599
Inline: True
```
**Symbols:**

```
ffffffff816ec840-ffffffff816eca98: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff816ecaa0-ffffffff816ecad7: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81766980)
Location: drivers/acpi/acpi_dbg.c:599
Inline: True
```
**Symbols:**

```
ffffffff81766980-ffffffff81766bd8: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff81766be0-ffffffff81766c17: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8189abf0)
Location: drivers/acpi/acpi_dbg.c:599
Inline: True
```
**Symbols:**

```
ffffffff8189abf0-ffffffff8189ae68: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff8189ae70-ffffffff8189aec4: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff819e31b0)
Location: drivers/acpi/acpi_dbg.c:599
Inline: True
```
**Symbols:**

```
ffffffff819e31b0-ffffffff819e3428: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff819e3440-ffffffff819e3494: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a2b7b0)
Location: drivers/acpi/acpi_dbg.c:599
Inline: True
```
**Symbols:**

```
ffffffff81a2b7b0-ffffffff81a2ba24: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff81a2ba40-ffffffff81a2baa4: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a76980)
Location: drivers/acpi/acpi_dbg.c:599
Inline: True
```
**Symbols:**

```
ffffffff81a76980-ffffffff81a76bf4: acpi_aml_read.part.0 (STB_LOCAL)
ffffffff81a76c10-ffffffff81a76c74: acpi_aml_read (STB_LOCAL)
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
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816349a0)
Location: drivers/acpi/acpi_dbg.c:606
Inline: True
```
**Symbols:**

```
ffffffff816349a0-ffffffff81634be8: acpi_aml_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t acpi_aml_read(struct file *file, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8164ecc0)
Location: drivers/acpi/acpi_dbg.c:606
Inline: True
```
**Symbols:**

```
ffffffff8164ecc0-ffffffff8164ef03: acpi_aml_read (STB_LOCAL)
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
