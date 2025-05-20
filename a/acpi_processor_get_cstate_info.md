# Function: <code>acpi_processor_get_cstate_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff814fbfee)
Location: drivers/acpi/processor_idle.c:578
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8151ecc2)
Location: drivers/acpi/processor_idle.c:579
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815301b1)
Location: drivers/acpi/processor_idle.c:579
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81590e81)
Location: drivers/acpi/processor_idle.c:581
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815c8285)
Location: drivers/acpi/processor_idle.c:585
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815e1845)
Location: drivers/acpi/processor_idle.c:586
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81613395)
Location: drivers/acpi/processor_idle.c:581
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81634895)
Location: drivers/acpi/processor_idle.c:581
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_processor_get_cstate_info(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e1d50)
Location: drivers/acpi/processor_idle.c:437
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff816e1d50-ffffffff816e1e2f: acpi_processor_get_cstate_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_processor_get_cstate_info(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816ffc30)
Location: drivers/acpi/processor_idle.c:429
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff816ffc30-ffffffff816ffd0f: acpi_processor_get_cstate_info (STB_LOCAL)
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
In drivers/acpi/processor_idle.c (ffffffff816e169e)
Location: drivers/acpi/processor_idle.c:465
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81759ae3)
Location: drivers/acpi/processor_idle.c:465
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff8188d2cf)
Location: drivers/acpi/processor_idle.c:464
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_cstate_info(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:463
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff819d48b0-ffffffff819d49db: acpi_processor_get_cstate_info (STB_LOCAL)
ffffffff82092641-ffffffff82092656: acpi_processor_get_cstate_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_cstate_info(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:463
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81a1c1d0-ffffffff81a1c420: acpi_processor_get_cstate_info (STB_LOCAL)
ffffffff82112f5d-ffffffff82112f72: acpi_processor_get_cstate_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_cstate_info(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_idle.c (0)
Location: drivers/acpi/processor_idle.c:463
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_hotplug
```
**Symbols:**

```
ffffffff81a674b0-ffffffff81a67700: acpi_processor_get_cstate_info (STB_LOCAL)
ffffffff821f0cb1-ffffffff821f0cc6: acpi_processor_get_cstate_info.cold (STB_LOCAL)
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
Location: drivers/acpi/processor_idle.c:927
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
In drivers/acpi/processor_idle.c (ffffffff81604395)
Location: drivers/acpi/processor_idle.c:581
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815ef445)
Location: drivers/acpi/processor_idle.c:581
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81628b75)
Location: drivers/acpi/processor_idle.c:581
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81642a25)
Location: drivers/acpi/processor_idle.c:581
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
