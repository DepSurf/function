# Function: <code>acpi_power_resource_add_dependent</code>

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
In drivers/acpi/power.c (ffffffff815cb39b)
Location: drivers/acpi/power.c:242
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff815ec61b)
Location: drivers/acpi/power.c:242
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_power_resource_add_dependent(struct acpi_power_resource *resource, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81698240)
Location: drivers/acpi/power.c:240
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
```
**Symbols:**

```
ffffffff81698240-ffffffff81698319: acpi_power_resource_add_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_power_resource_add_dependent(struct acpi_power_resource *resource, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b5370)
Location: drivers/acpi/power.c:240
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
```
**Symbols:**

```
ffffffff816b5370-ffffffff816b5449: acpi_power_resource_add_dependent (STB_LOCAL)
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
In drivers/acpi/power.c (ffffffff816972f1)
Location: drivers/acpi/power.c:238
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff8170d0b1)
Location: drivers/acpi/power.c:249
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff8183b981)
Location: drivers/acpi/power.c:249
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff8197116e)
Location: drivers/acpi/power.c:249
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff819b77ee)
Location: drivers/acpi/power.c:250
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff81a01d9a)
Location: drivers/acpi/power.c:250
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffff800010777cb4)
Location: drivers/acpi/power.c:242
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff815db80b)
Location: drivers/acpi/power.c:242
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff815c6e4b)
Location: drivers/acpi/power.c:242
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff815e08fb)
Location: drivers/acpi/power.c:242
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
In drivers/acpi/power.c (ffffffff815fa7bb)
Location: drivers/acpi/power.c:242
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_device_power_add_dependent
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
</ul>
