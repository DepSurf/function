# Function: <code>usb_acpi_find_port</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *usb_acpi_find_port(struct acpi_device *parent, int raw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff816c3f10)
Location: drivers/usb/core/usb-acpi.c:130
Inline: True
```
**Symbols:**

```
ffffffff816c3f10-ffffffff816c3f5d: usb_acpi_find_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *usb_acpi_find_port(struct acpi_device *parent, int raw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff8172fcf0)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
```
**Symbols:**

```
ffffffff8172fcf0-ffffffff8172fd3d: usb_acpi_find_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *usb_acpi_find_port(struct acpi_device *parent, int raw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff8176ee10)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
```
**Symbols:**

```
ffffffff8176ee10-ffffffff8176ee5b: usb_acpi_find_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *usb_acpi_find_port(struct acpi_device *parent, int raw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81793490)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
```
**Symbols:**

```
ffffffff81793490-ffffffff817934db: usb_acpi_find_port (STB_LOCAL)
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
In drivers/usb/core/usb-acpi.c (ffffffff817d1dcf)
Location: drivers/usb/core/usb-acpi.c:126
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
In drivers/usb/core/usb-acpi.c (ffffffff81802c9f)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff818d3419)
Location: drivers/usb/core/usb-acpi.c:127
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff818dd7b9)
Location: drivers/usb/core/usb-acpi.c:127
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
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
In drivers/usb/core/usb-acpi.c (ffffffff818c0b29)
Location: drivers/usb/core/usb-acpi.c:127
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
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
In drivers/usb/core/usb-acpi.c (ffffffff81957269)
Location: drivers/usb/core/usb-acpi.c:127
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
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
In drivers/usb/core/usb-acpi.c (ffffffff81ab0f30)
Location: drivers/usb/core/usb-acpi.c:127
Inline: True
Inline callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffff800010a37594)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
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
In drivers/usb/core/usb-acpi.c (ffffffff817bb07f)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
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
In drivers/usb/core/usb-acpi.c (ffffffff817aca9f)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
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
In drivers/usb/core/usb-acpi.c (ffffffff817f7b1f)
Location: drivers/usb/core/usb-acpi.c:126
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
In drivers/usb/core/usb-acpi.c (ffffffff81811d5f)
Location: drivers/usb/core/usb-acpi.c:126
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
