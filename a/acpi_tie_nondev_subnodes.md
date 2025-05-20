# Function: <code>acpi_tie_nondev_subnodes</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_tie_nondev_subnodes(struct acpi_device_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819751a0)
Location: drivers/acpi/property.c:366
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_tie_nondev_subnodes
```
**Symbols:**

```
ffffffff819751a0-ffffffff8197522b: acpi_tie_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_tie_nondev_subnodes(struct acpi_device_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bb9e0)
Location: drivers/acpi/property.c:366
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_tie_nondev_subnodes
```
**Symbols:**

```
ffffffff819bb9e0-ffffffff819bba6b: acpi_tie_nondev_subnodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_tie_nondev_subnodes(struct acpi_device_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a06210)
Location: drivers/acpi/property.c:370
Inline: False
Direct callers:
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_tie_nondev_subnodes
```
**Symbols:**

```
ffffffff81a06210-ffffffff81a0629b: acpi_tie_nondev_subnodes (STB_LOCAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
