# Function: <code>acpi_node_get_property_reference</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_node_get_property_reference(struct fwnode_handle *fwnode, const char *name, size_t index, struct acpi_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8148a939)
Location: drivers/acpi/property.c:579
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
**Symbols:**

```
ffffffff8148a939-ffffffff8148aa9c: acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_node_get_property_reference(struct fwnode_handle *fwnode, const char *name, size_t index, struct acpi_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814d9741)
Location: drivers/acpi/property.c:579
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
**Symbols:**

```
ffffffff814d9741-ffffffff814d98a0: acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150c7ce)
Location: include/linux/acpi.h:1016
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff8154f3ce)
Location: include/linux/acpi.h:1042
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff81585c79)
Location: include/linux/acpi.h:1075
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff8159cfe8)
Location: include/linux/acpi.h:1084
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff815ce548)
Location: include/linux/acpi.h:1073
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff815ef7c8)
Location: include/linux/acpi.h:1032
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff8169b9d8)
Location: include/linux/acpi.h:1083
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff816b87f8)
Location: include/linux/acpi.h:1110
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff8169a799)
Location: include/linux/acpi.h:1127
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff817105f9)
Location: include/linux/acpi.h:1159
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff8183f628)
Location: include/linux/acpi.h:1230
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff81975e98)
Location: include/linux/acpi.h:1263
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff819bc778)
Location: include/linux/acpi.h:1283
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff81a07068)
Location: include/linux/acpi.h:1281
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffff80001077a560)
Location: include/linux/acpi.h:1032
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff815de458)
Location: include/linux/acpi.h:1032
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff815c9a98)
Location: include/linux/acpi.h:1032
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff815e3aa8)
Location: include/linux/acpi.h:1032
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
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
In drivers/acpi/property.c (ffffffff815fd968)
Location: include/linux/acpi.h:1032
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
