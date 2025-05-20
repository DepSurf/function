# Function: <code>__get_state</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __get_state(acpi_handle handle, u8 *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170cb80)
Location: drivers/acpi/power.c:186
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_get_inferred_state
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
```
**Symbols:**

```
ffffffff8170cb80-ffffffff8170cc26: __get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __get_state(acpi_handle handle, u8 *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183b2e0)
Location: drivers/acpi/power.c:186
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_get_inferred_state
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
  - drivers/acpi/power.c:acpi_power_get_state
```
**Symbols:**

```
ffffffff8183b2e0-ffffffff8183b395: __get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __get_state(acpi_handle handle, u8 *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81970a70)
Location: drivers/acpi/power.c:186
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_get_inferred_state
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
```
**Symbols:**

```
ffffffff81970a70-ffffffff81970b25: __get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __get_state(acpi_handle handle, u8 *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b70f0)
Location: drivers/acpi/power.c:187
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_get_inferred_state
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
```
**Symbols:**

```
ffffffff819b70f0-ffffffff819b71a5: __get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __get_state(acpi_handle handle, u8 *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a016a0)
Location: drivers/acpi/power.c:187
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_get_inferred_state
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
```
**Symbols:**

```
ffffffff81a016a0-ffffffff81a01755: __get_state (STB_LOCAL)
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
