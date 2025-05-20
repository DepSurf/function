# Function: <code>usb_acpi_get_companion_for_port</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff817d1d70)
Location: drivers/usb/core/usb-acpi.c:143
Inline: True
```
**Symbols:**

```
ffffffff817d1d70-ffffffff817d1e5c: usb_acpi_get_companion_for_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81802c40)
Location: drivers/usb/core/usb-acpi.c:143
Inline: True
```
**Symbols:**

```
ffffffff81802c40-ffffffff81802d2c: usb_acpi_get_companion_for_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff818d33b0)
Location: drivers/usb/core/usb-acpi.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port
```
**Symbols:**

```
ffffffff818d33b0-ffffffff818d34ae: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff818dd750)
Location: drivers/usb/core/usb-acpi.c:144
Inline: False
Direct callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port
```
**Symbols:**

```
ffffffff818dd750-ffffffff818dd84e: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff818c0ac0)
Location: drivers/usb/core/usb-acpi.c:144
Inline: False
```
**Symbols:**

```
ffffffff818c0ac0-ffffffff818c0bbe: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81957200)
Location: drivers/usb/core/usb-acpi.c:144
Inline: False
```
**Symbols:**

```
ffffffff81957200-ffffffff819572fe: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81ab0ee0)
Location: drivers/usb/core/usb-acpi.c:144
Inline: False
```
**Symbols:**

```
ffffffff81ab0ee0-ffffffff81ab0fea: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81c393a0)
Location: drivers/usb/core/usb-acpi.c:193
Inline: False
```
**Symbols:**

```
ffffffff81c393a0-ffffffff81c39436: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81ca05c0)
Location: drivers/usb/core/usb-acpi.c:189
Inline: False
```
**Symbols:**

```
ffffffff81ca05c0-ffffffff81ca0656: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_device *usb_acpi_get_companion_for_port(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81d55210)
Location: drivers/usb/core/usb-acpi.c:189
Inline: False
```
**Symbols:**

```
ffffffff81d55210-ffffffff81d552a6: usb_acpi_get_companion_for_port (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffff800010a37538)
Location: drivers/usb/core/usb-acpi.c:143
Inline: True
```
**Symbols:**

```
ffff800010a37538-ffff800010a3763c: usb_acpi_get_companion_for_port.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff817bb020)
Location: drivers/usb/core/usb-acpi.c:143
Inline: True
```
**Symbols:**

```
ffffffff817bb020-ffffffff817bb10c: usb_acpi_get_companion_for_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff817aca40)
Location: drivers/usb/core/usb-acpi.c:143
Inline: True
```
**Symbols:**

```
ffffffff817aca40-ffffffff817acb2c: usb_acpi_get_companion_for_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff817f7ac0)
Location: drivers/usb/core/usb-acpi.c:143
Inline: True
```
**Symbols:**

```
ffffffff817f7ac0-ffffffff817f7bac: usb_acpi_get_companion_for_port.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb-acpi.c (ffffffff81811d00)
Location: drivers/usb/core/usb-acpi.c:143
Inline: True
```
**Symbols:**

```
ffffffff81811d00-ffffffff81811dec: usb_acpi_get_companion_for_port.isra.0 (STB_LOCAL)
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
