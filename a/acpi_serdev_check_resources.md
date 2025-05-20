# Function: <code>acpi_serdev_check_resources</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_serdev_check_resources(struct serdev_controller *ctrl, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff8176dfd0)
Location: drivers/tty/serdev/core.c:619
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff8176dfd0-ffffffff8176e11f: acpi_serdev_check_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_serdev_check_resources(struct serdev_controller *ctrl, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81788990)
Location: drivers/tty/serdev/core.c:619
Inline: False
Direct callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
**Symbols:**

```
ffffffff81788990-ffffffff81788ae2: acpi_serdev_check_resources (STB_LOCAL)
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
In drivers/tty/serdev/core.c (ffffffff8176c510)
Location: drivers/tty/serdev/core.c:619
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
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
In drivers/tty/serdev/core.c (ffffffff817f1c50)
Location: drivers/tty/serdev/core.c:639
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
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
In drivers/tty/serdev/core.c (ffffffff819323a2)
Location: drivers/tty/serdev/core.c:639
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
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
In drivers/tty/serdev/core.c (ffffffff81a90e7f)
Location: drivers/tty/serdev/core.c:639
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
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
In drivers/tty/serdev/core.c (ffffffff81adc68e)
Location: drivers/tty/serdev/core.c:650
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
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
In drivers/tty/serdev/core.c (ffffffff81b2f9ae)
Location: drivers/tty/serdev/core.c:643
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
