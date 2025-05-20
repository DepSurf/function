# Function: <code>disabled_by_idle_boot_param</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int disabled_by_idle_boot_param();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814ac559)
Location: drivers/acpi/processor_idle.c:67
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
  - drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
```
**Symbols:**

```
ffffffff814ac559-ffffffff814ac578: disabled_by_idle_boot_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int disabled_by_idle_boot_param();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fb8b3)
Location: drivers/acpi/processor_idle.c:71
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff814fb8b3-ffffffff814fb8d2: disabled_by_idle_boot_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int disabled_by_idle_boot_param();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8151e587)
Location: drivers/acpi/processor_idle.c:72
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff8151e587-ffffffff8151e5a6: disabled_by_idle_boot_param (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81531205)
Location: drivers/acpi/processor_idle.c:72
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff815921f5)
Location: drivers/acpi/processor_idle.c:74
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff815c9574)
Location: drivers/acpi/processor_idle.c:74
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff815e2b54)
Location: drivers/acpi/processor_idle.c:74
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff816146e3)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff81635bd3)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff816e2833)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff81700503)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff816e2063)
Location: drivers/acpi/processor_idle.c:59
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff8175a855)
Location: drivers/acpi/processor_idle.c:59
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff8188dbe5)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff819d55e5)
Location: drivers/acpi/processor_idle.c:62
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff81a1cf35)
Location: drivers/acpi/processor_idle.c:62
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff81a68245)
Location: drivers/acpi/processor_idle.c:62
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:925
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
In drivers/acpi/processor_idle.c (ffffffff816053c3)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff815f0473)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff81629eb3)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
In drivers/acpi/processor_idle.c (ffffffff81643d53)
Location: drivers/acpi/processor_idle.c:61
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_exit
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
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
</ul>
