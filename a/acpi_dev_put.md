# Function: <code>acpi_dev_put</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b89ca)
Location: include/acpi/acpi_bus.h:686
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
In drivers/acpi/sleep.c (ffffffff815d9c08)
Location: include/acpi/acpi_bus.h:686
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
In drivers/acpi/sleep.c (ffffffff81683e2f)
Location: include/acpi/acpi_bus.h:689
Inline: True
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
In drivers/acpi/sleep.c (ffffffff81c00d9e)
Location: include/acpi/acpi_bus.h:690
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81683354)
Location: include/acpi/acpi_bus.h:712
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
```
```
In drivers/acpi/sleep.c (ffffffff81bf27f1)
Location: include/acpi/acpi_bus.h:712
Inline: True
```
```
In drivers/acpi/device_sysfs.c (ffffffff8168529d)
Location: include/acpi/acpi_bus.h:712
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:eject_store
```
```
In drivers/acpi/glue.c (ffffffff81689339)
Location: include/acpi/acpi_bus.h:712
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/scan.c (ffffffff83209e1f)
Location: include/acpi/acpi_bus.h:712
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/firmware/efi/dev-path-parser.c (ffffffff83224749)
Location: include/acpi/acpi_bus.h:712
Inline: True
Inline callers:
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f84a4)
Location: include/acpi/acpi_bus.h:722
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
```
```
In drivers/acpi/sleep.c (ffffffff81cef0d5)
Location: include/acpi/acpi_bus.h:722
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_sysfs.c (ffffffff816fa55d)
Location: include/acpi/acpi_bus.h:722
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:eject_store
```
```
In drivers/acpi/device_pm.c (ffffffff816fba27)
Location: include/acpi/acpi_bus.h:722
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff816fda5a)
Location: include/acpi/acpi_bus.h:722
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/glue.c (ffffffff816fe779)
Location: include/acpi/acpi_bus.h:722
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/scan.c (ffffffff832f21a1)
Location: include/acpi/acpi_bus.h:722
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/firmware/efi/dev-path-parser.c (ffffffff8330e543)
Location: include/acpi/acpi_bus.h:722
Inline: True
Inline callers:
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825634)
Location: include/acpi/acpi_bus.h:760
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
```
```
In drivers/acpi/sleep.c (ffffffff81eb6861)
Location: include/acpi/acpi_bus.h:760
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_sysfs.c (ffffffff8182793b)
Location: include/acpi/acpi_bus.h:760
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:eject_store
```
```
In drivers/acpi/device_pm.c (ffffffff81828f57)
Location: include/acpi/acpi_bus.h:760
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff8182b2ea)
Location: include/acpi/acpi_bus.h:760
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/glue.c (ffffffff8182c138)
Location: include/acpi/acpi_bus.h:760
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/scan.c (ffffffff8182d790)
Location: include/acpi/acpi_bus.h:760
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/firmware/efi/dev-path-parser.c (ffffffff834c8135)
Location: include/acpi/acpi_bus.h:760
Inline: True
Inline callers:
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819569a6)
Location: include/acpi/acpi_bus.h:785
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
```
```
In drivers/acpi/sleep.c (ffffffff81958400)
Location: include/acpi/acpi_bus.h:785
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_sysfs.c (ffffffff8195990b)
Location: include/acpi/acpi_bus.h:785
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:eject_store
```
```
In drivers/acpi/device_pm.c (ffffffff8195b0e7)
Location: include/acpi/acpi_bus.h:785
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff8195d9d6)
Location: include/acpi/acpi_bus.h:785
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/glue.c (ffffffff8195eff8)
Location: include/acpi/acpi_bus.h:785
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/scan.c (ffffffff81960f55)
Location: include/acpi/acpi_bus.h:785
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/firmware/efi/dev-path-parser.c (ffffffff83f093ca)
Location: include/acpi/acpi_bus.h:785
Inline: True
Inline callers:
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199cda6)
Location: include/acpi/acpi_bus.h:802
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
```
```
In drivers/acpi/sleep.c (ffffffff8199e8e0)
Location: include/acpi/acpi_bus.h:802
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_sysfs.c (ffffffff8199fd6b)
Location: include/acpi/acpi_bus.h:802
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:eject_store
```
```
In drivers/acpi/device_pm.c (ffffffff819a15b7)
Location: include/acpi/acpi_bus.h:802
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff819a3b4b)
Location: include/acpi/acpi_bus.h:802
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/glue.c (ffffffff819a508d)
Location: include/acpi/acpi_bus.h:802
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/scan.c (ffffffff819a7355)
Location: include/acpi/acpi_bus.h:802
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/firmware/efi/dev-path-parser.c (ffffffff8372f4ee)
Location: include/acpi/acpi_bus.h:802
Inline: True
Inline callers:
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e4e16)
Location: include/acpi/acpi_bus.h:966
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_dev_get_next_match_dev
```
```
In drivers/acpi/sleep.c (ffffffff819e6f80)
Location: include/acpi/acpi_bus.h:966
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_pm_finish
```
```
In drivers/acpi/device_sysfs.c (ffffffff819e83db)
Location: include/acpi/acpi_bus.h:966
Inline: True
Inline callers:
  - drivers/acpi/device_sysfs.c:eject_store
```
```
In drivers/acpi/device_pm.c (ffffffff819e9c67)
Location: include/acpi/acpi_bus.h:966
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff819ec27b)
Location: include/acpi/acpi_bus.h:966
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/glue.c (ffffffff819ed9dd)
Location: include/acpi/acpi_bus.h:966
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_unbind_one
  - drivers/acpi/glue.c:acpi_bind_one
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/scan.c (ffffffff819efd45)
Location: include/acpi/acpi_bus.h:966
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_scan_clear_dep_fn
  - drivers/acpi/scan.c:acpi_device_del_work_fn
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/firmware/efi/dev-path-parser.c (ffffffff839639ea)
Location: include/acpi/acpi_bus.h:966
Inline: True
Inline callers:
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cc3fb)
Location: include/acpi/acpi_bus.h:686
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
In drivers/acpi/sleep.c (ffffffff815b5f62)
Location: include/acpi/acpi_bus.h:686
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
In drivers/acpi/sleep.c (ffffffff815cdee8)
Location: include/acpi/acpi_bus.h:686
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
In drivers/acpi/sleep.c (ffffffff815e7da8)
Location: include/acpi/acpi_bus.h:686
Inline: True
```
</details>
</li>
</ul>

## Differences
