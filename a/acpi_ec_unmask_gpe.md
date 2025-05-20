# Function: <code>acpi_ec_unmask_gpe</code>

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
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815450d0)
Location: drivers/acpi/ec.c:436
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff815450d0-ffffffff81545187: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8157b770)
Location: drivers/acpi/ec.c:436
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff8157b770-ffffffff8157b827: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81592d90)
Location: drivers/acpi/ec.c:436
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff81592d90-ffffffff81592e47: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c3d30)
Location: drivers/acpi/ec.c:426
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff815c3d30-ffffffff815c3def: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e4f70)
Location: drivers/acpi/ec.c:428
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff815e4f70-ffffffff815e502f: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff8000107708e0)
Location: drivers/acpi/ec.c:428
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffff8000107708e0-ffff800010770974: acpi_ec_unmask_gpe (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d6e60)
Location: drivers/acpi/ec.c:428
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff815d6e60-ffffffff815d6f1f: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c0a20)
Location: drivers/acpi/ec.c:428
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff815c0a20-ffffffff815c0adf: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d9250)
Location: drivers/acpi/ec.c:428
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff815d9250-ffffffff815d930f: acpi_ec_unmask_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_unmask_gpe(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f3110)
Location: drivers/acpi/ec.c:428
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_complete_query
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff815f3110-ffffffff815f31cf: acpi_ec_unmask_gpe (STB_LOCAL)
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
