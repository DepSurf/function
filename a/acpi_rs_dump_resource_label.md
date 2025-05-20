# Function: <code>acpi_rs_dump_resource_label</code>

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
In drivers/acpi/acpica/rsdump.c (ffffffff8158dbf8)
Location: drivers/acpi/acpica/rsdump.c:453
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff815c51fb)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff815de7a1)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff816102cd)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff81631776)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_rs_dump_resource_label(char *title, struct acpi_resource_label *resource_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff816dde23)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff816dde23-ffffffff816dde57: acpi_rs_dump_resource_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_rs_dump_resource_label(char *title, struct acpi_resource_label *resource_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff816fbeb9)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff816fbeb9-ffffffff816fbeed: acpi_rs_dump_resource_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_rs_dump_resource_label(char *title, struct acpi_resource_label *resource_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff816ddcc4)
Location: drivers/acpi/acpica/rsdump.c:425
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff816ddcc4-ffffffff816ddcf8: acpi_rs_dump_resource_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_rs_dump_resource_label(char *title, struct acpi_resource_label *resource_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff81755db4)
Location: drivers/acpi/acpica/rsdump.c:425
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff81755db4-ffffffff81755de8: acpi_rs_dump_resource_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_rs_dump_resource_label(char *title, struct acpi_resource_label *resource_label);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff81888e77)
Location: drivers/acpi/acpica/rsdump.c:425
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
```
**Symbols:**

```
ffffffff81888e77-ffffffff81888eba: acpi_rs_dump_resource_label (STB_LOCAL)
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
In drivers/acpi/acpica/rsdump.c (ffffffff819cf67c)
Location: drivers/acpi/acpica/rsdump.c:425
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff81a16bdb)
Location: drivers/acpi/acpica/rsdump.c:425
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff81a61dbb)
Location: drivers/acpi/acpica/rsdump.c:425
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsdump.c (ffffffff81625a56)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
In drivers/acpi/acpica/rsdump.c (ffffffff8163f906)
Location: drivers/acpi/acpica/rsdump.c:417
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
  - drivers/acpi/acpica/rsdump.c:acpi_rs_dump_descriptor
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
</ul>
