# Function: <code>__acpi_match_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct acpi_device_id *__acpi_match_device(struct acpi_device *device, const struct acpi_device_id *ids, const struct of_device_id *of_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147e8c7)
Location: drivers/acpi/bus.c:617
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_match_device_ids
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff8147e8c7-ffffffff8147e9fc: __acpi_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct acpi_device_id *__acpi_match_device(struct acpi_device *device, const struct acpi_device_id *ids, const struct of_device_id *of_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cd0dd)
Location: drivers/acpi/bus.c:693
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_match_device_ids
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff814cd0dd-ffffffff814cd214: __acpi_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct acpi_device_id *__acpi_match_device(struct acpi_device *device, const struct acpi_device_id *ids, const struct of_device_id *of_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ef00b)
Location: drivers/acpi/bus.c:703
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_match_device_ids
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff814ef00b-ffffffff814ef142: __acpi_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct acpi_device_id *__acpi_match_device(struct acpi_device *device, const struct acpi_device_id *ids, const struct of_device_id *of_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fbe70)
Location: drivers/acpi/bus.c:731
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff814fbe70-ffffffff814fbfd1: __acpi_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct acpi_device_id *__acpi_match_device(struct acpi_device *device, const struct acpi_device_id *ids, const struct of_device_id *of_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153dbe0)
Location: drivers/acpi/bus.c:758
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff8153dbe0-ffffffff8153dd41: __acpi_match_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81573e10)
Location: drivers/acpi/bus.c:770
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff81573cb0-ffffffff81573dfc: __acpi_match_device.part.6.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158ba30)
Location: drivers/acpi/bus.c:739
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff8158b8d0-ffffffff8158ba1c: __acpi_match_device.part.6.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bc7a0)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff815bc640-ffffffff815bc78e: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
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
In drivers/acpi/bus.c (ffffffff815dda60)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff815dd900-ffffffff815dda4e: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688211)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff81687e10-ffffffff81687f5e: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a5f91)
Location: drivers/acpi/bus.c:731
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff816a5b80-ffffffff816a5cce: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688ae1)
Location: drivers/acpi/bus.c:810
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff81688880-ffffffff816889c7: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fdf21)
Location: drivers/acpi/bus.c:812
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff816fdcc0-ffffffff816fde07: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182b5e0)
Location: drivers/acpi/bus.c:849
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff8182b5e0-ffffffff8182b75b: __acpi_match_device.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195dee0)
Location: drivers/acpi/bus.c:855
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff8195dee0-ffffffff8195e058: __acpi_match_device.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a40a0)
Location: drivers/acpi/bus.c:811
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff819a40a0-ffffffff819a4218: __acpi_match_device.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ec7d0)
Location: drivers/acpi/bus.c:861
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_driver_match_device
  - drivers/acpi/bus.c:acpi_device_get_match_data
```
**Symbols:**

```
ffffffff819ec7d0-ffffffff819ec948: __acpi_match_device.constprop.0 (STB_LOCAL)
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
In drivers/acpi/bus.c (ffff800010769d00)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffff800010769b68-ffff800010769cd8: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
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
In drivers/acpi/bus.c (ffffffff815cff40)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff815cfde0-ffffffff815cff2e: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
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
In drivers/acpi/bus.c (ffffffff815b9b00)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff815b99a0-ffffffff815b9aee: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
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
In drivers/acpi/bus.c (ffffffff815d1d40)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff815d1be0-ffffffff815d1d2e: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
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
In drivers/acpi/bus.c (ffffffff815ebc00)
Location: drivers/acpi/bus.c:726
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_match_device
```
**Symbols:**

```
ffffffff815ebaa0-ffffffff815ebbee: __acpi_match_device.part.0.constprop.0 (STB_LOCAL)
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
