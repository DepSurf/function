# Function: <code>acpi_aml_open</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159b380)
Location: drivers/acpi/acpi_dbg.c:472
Inline: False
```
**Symbols:**

```
ffffffff8159b380-ffffffff8159b506: acpi_aml_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:472
Inline: False
```
**Symbols:**

```
ffffffff815d3010-ffffffff815d317e: acpi_aml_open (STB_LOCAL)
ffffffff815d3d82-ffffffff815d3d99: acpi_aml_open.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:472
Inline: False
```
**Symbols:**

```
ffffffff815ec7c0-ffffffff815ec92e: acpi_aml_open (STB_LOCAL)
ffffffff815ed532-ffffffff815ed549: acpi_aml_open.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:469
Inline: False
```
**Symbols:**

```
ffffffff8161e590-ffffffff8161e6fe: acpi_aml_open (STB_LOCAL)
ffffffff8161f2dc-ffffffff8161f2f3: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:469
Inline: False
```
**Symbols:**

```
ffffffff81640040-ffffffff816401ae: acpi_aml_open (STB_LOCAL)
ffffffff81640dbc-ffffffff81640dd3: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:469
Inline: False
```
**Symbols:**

```
ffffffff816ecda0-ffffffff816ecf0e: acpi_aml_open (STB_LOCAL)
ffffffff816ede61-ffffffff816ede78: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:462
Inline: False
```
**Symbols:**

```
ffffffff8170a390-ffffffff8170a4fe: acpi_aml_open (STB_LOCAL)
ffffffff81c0331b-ffffffff81c03332: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:462
Inline: False
```
**Symbols:**

```
ffffffff816eba60-ffffffff816ebbce: acpi_aml_open (STB_LOCAL)
ffffffff81bf4d0d-ffffffff81bf4d24: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:462
Inline: False
```
**Symbols:**

```
ffffffff81765b80-ffffffff81765ce5: acpi_aml_open (STB_LOCAL)
ffffffff81cf203f-ffffffff81cf2056: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:462
Inline: False
```
**Symbols:**

```
ffffffff81899f80-ffffffff8189a0f1: acpi_aml_open (STB_LOCAL)
ffffffff81eba0b2-ffffffff81eba0c9: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff819e2460)
Location: drivers/acpi/acpi_dbg.c:462
Inline: False
```
**Symbols:**

```
ffffffff819e2460-ffffffff819e25ee: acpi_aml_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a2aa60)
Location: drivers/acpi/acpi_dbg.c:462
Inline: False
```
**Symbols:**

```
ffffffff81a2aa60-ffffffff81a2abee: acpi_aml_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a75c30)
Location: drivers/acpi/acpi_dbg.c:462
Inline: False
```
**Symbols:**

```
ffffffff81a75c30-ffffffff81a75dbe: acpi_aml_open (STB_LOCAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:469
Inline: False
```
**Symbols:**

```
ffffffff81633e80-ffffffff81633fee: acpi_aml_open (STB_LOCAL)
ffffffff81634bfc-ffffffff81634c13: acpi_aml_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_aml_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_dbg.c (0)
Location: drivers/acpi/acpi_dbg.c:469
Inline: False
```
**Symbols:**

```
ffffffff8164e1a0-ffffffff8164e30e: acpi_aml_open (STB_LOCAL)
ffffffff8164ef17-ffffffff8164ef2e: acpi_aml_open.cold (STB_LOCAL)
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
