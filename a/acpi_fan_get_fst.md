# Function: <code>acpi_fan_get_fst</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_fan_get_fst(struct acpi_device *device, struct acpi_fan_fst *fst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/fan_core.c (0)
Location: drivers/acpi/fan_core.c:78
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
  - drivers/acpi/fan_attr.c:show_fan_speed
```
**Symbols:**

```
ffffffff81eb9238-ffffffff81eb9274: acpi_fan_get_fst.cold (STB_LOCAL)
ffffffff8188aeb0-ffffffff8188af8e: acpi_fan_get_fst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_fan_get_fst(struct acpi_device *device, struct acpi_fan_fst *fst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan_core.c (ffffffff819d1ae0)
Location: drivers/acpi/fan_core.c:47
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
  - drivers/acpi/fan_attr.c:show_fan_speed
```
**Symbols:**

```
ffffffff819d1ae0-ffffffff819d1be6: acpi_fan_get_fst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_fan_get_fst(struct acpi_device *device, struct acpi_fan_fst *fst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan_core.c (ffffffff81a190e0)
Location: drivers/acpi/fan_core.c:47
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
  - drivers/acpi/fan_attr.c:show_fan_speed
```
**Symbols:**

```
ffffffff81a190e0-ffffffff81a191e6: acpi_fan_get_fst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_fan_get_fst(struct acpi_device *device, struct acpi_fan_fst *fst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan_core.c (ffffffff81a643b0)
Location: drivers/acpi/fan_core.c:47
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:fan_get_cur_state
  - drivers/acpi/fan_attr.c:show_fan_speed
```
**Symbols:**

```
ffffffff81a643b0-ffffffff81a644b6: acpi_fan_get_fst (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
