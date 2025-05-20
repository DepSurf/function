# Function: <code>acpi_ds_resolve_package_element</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff8155504d)
Location: drivers/acpi/acpica/dspkginit.c:349
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
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
In drivers/acpi/acpica/dspkginit.c (ffffffff8158b9ef)
Location: drivers/acpi/acpica/dspkginit.c:355
Inline: True
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
In drivers/acpi/acpica/dspkginit.c (ffffffff815a3fbe)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
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
In drivers/acpi/acpica/dspkginit.c (ffffffff815d56b5)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
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
In drivers/acpi/acpica/dspkginit.c (ffffffff815f692d)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a29b5)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff816a29b5-ffffffff816a2c82: acpi_ds_resolve_package_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff816c01ab)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff816c01ab-ffffffff816c0478: acpi_ds_resolve_package_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a222d)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff816a222d-ffffffff816a250f: acpi_ds_resolve_package_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81718b63)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff81718b63-ffffffff81718e45: acpi_ds_resolve_package_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81848875)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff81848875-ffffffff81848b7d: acpi_ds_resolve_package_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff819809b0)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff819809b0-ffffffff81980d01: acpi_ds_resolve_package_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff819c7470)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff819c7470-ffffffff819c77c6: acpi_ds_resolve_package_element (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object **element_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81a11ec0)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
```
**Symbols:**

```
ffffffff81a11ec0-ffffffff81a12216: acpi_ds_resolve_package_element (STB_LOCAL)
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
In drivers/acpi/acpica/dspkginit.c (ffff80001077f49c)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
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
In drivers/acpi/acpica/dspkginit.c (ffffffff815e2fe8)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
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
In drivers/acpi/acpica/dspkginit.c (ffffffff815ce659)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
Inline callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element
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
In drivers/acpi/acpica/dspkginit.c (ffffffff815eac0d)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
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
In drivers/acpi/acpica/dspkginit.c (ffffffff81604abd)
Location: drivers/acpi/acpica/dspkginit.c:381
Inline: True
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
