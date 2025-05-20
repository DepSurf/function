# Function: <code>acpi_dev_for_each_child</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_dev_for_each_child(struct acpi_device *adev, int (*fn)(struct acpi_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182bd00)
Location: drivers/acpi/bus.c:1105
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr
```
**Symbols:**

```
ffffffff8182bd00-ffffffff8182bd5b: acpi_dev_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_dev_for_each_child(struct acpi_device *adev, int (*fn)(struct acpi_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195d820)
Location: drivers/acpi/bus.c:1105
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/glue.c:acpi_find_child_by_adr
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/container.c:acpi_container_offline
```
**Symbols:**

```
ffffffff8195d820-ffffffff8195d87b: acpi_dev_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dev_for_each_child(struct acpi_device *adev, int (*fn)(struct acpi_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a3a40)
Location: drivers/acpi/bus.c:1078
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/glue.c:acpi_find_child_by_adr
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/container.c:acpi_container_offline
```
**Symbols:**

```
ffffffff819a3a40-ffffffff819a3a9b: acpi_dev_for_each_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dev_for_each_child(struct acpi_device *adev, int (*fn)(struct acpi_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ec170)
Location: drivers/acpi/bus.c:1130
Inline: False
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_children
  - drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended
  - drivers/acpi/glue.c:acpi_find_child_by_adr
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/property.c:acpi_get_next_subnode
  - drivers/acpi/container.c:acpi_container_offline
```
**Symbols:**

```
ffffffff819ec170-ffffffff819ec1cb: acpi_dev_for_each_child (STB_GLOBAL)
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
