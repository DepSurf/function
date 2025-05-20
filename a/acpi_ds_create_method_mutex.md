# Function: <code>acpi_ds_create_method_mutex</code>

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
In drivers/acpi/acpica/dsmethod.c (ffffffff8148c61a)
Location: drivers/acpi/acpica/dsmethod.c:278
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
In drivers/acpi/acpica/dsmethod.c (ffffffff814db41a)
Location: drivers/acpi/acpica/dsmethod.c:277
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
In drivers/acpi/acpica/dsmethod.c (ffffffff814fdd11)
Location: drivers/acpi/acpica/dsmethod.c:277
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
In drivers/acpi/acpica/dsmethod.c (ffffffff8150e1d8)
Location: drivers/acpi/acpica/dsmethod.c:281
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815527c0)
Location: drivers/acpi/acpica/dsmethod.c:281
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff81589108)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815a164a)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815d2ca7)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815f3f1a)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ds_create_method_mutex(union acpi_operand_object *method_desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8169fba5)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
**Symbols:**

```
ffffffff8169fba5-ffffffff8169fc96: acpi_ds_create_method_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ds_create_method_mutex(union acpi_operand_object *method_desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff816bd3bd)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
**Symbols:**

```
ffffffff816bd3bd-ffffffff816bd4ae: acpi_ds_create_method_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8169f89b)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff81715e9b)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff818459a4)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff8197d4d5)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff819c3f85)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dsmethod.c (ffffffff81a0e9a5)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffff80001077db64)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815e1899)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815ccf14)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff815e81fa)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
In drivers/acpi/acpica/dsmethod.c (ffffffff816020aa)
Location: drivers/acpi/acpica/dsmethod.c:247
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_begin_method_execution
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
</ul>
