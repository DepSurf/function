# Function: <code>acpi_rs_validate_parameters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff814a3ea5)
Location: drivers/acpi/acpica/rsxface.c:93
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
```
**Symbols:**

```
ffffffff814a3ea5-ffffffff814a3eed: acpi_rs_validate_parameters.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff814f324d)
Location: drivers/acpi/acpica/rsxface.c:93
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff814f31e8-ffffffff814f3230: acpi_rs_validate_parameters.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81515d9b)
Location: drivers/acpi/acpica/rsxface.c:93
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff81515d36-ffffffff81515d7e: acpi_rs_validate_parameters.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815265b8)
Location: drivers/acpi/acpica/rsxface.c:93
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff815265b8-ffffffff8152660b: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8157d33e)
Location: drivers/acpi/acpica/rsxface.c:93
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff8157d33e-ffffffff8157d45d: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815b4514)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff815b4514-ffffffff815b4633: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815cd8d0)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff815cd8d0-ffffffff815cd9ef: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815ff127)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff815ff127-ffffffff815ff24d: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816205d1)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff816205d1-ffffffff816206f7: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816ccb60)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff816ccb60-ffffffff816ccc86: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816eab77)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff816eab77-ffffffff816eac9d: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816cca89)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff816cca89-ffffffff816ccbaf: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81743f59)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff81743f59-ffffffff8174407f: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81875af4)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_set_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff81875af4-ffffffff81875c22: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff819b7430)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_set_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff819b7430-ffffffff819b75a1: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff819fe580)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_set_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff819fe580-ffffffff819fe6f1: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81a49400)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_set_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff81a49400-ffffffff81a49571: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffff8000107960c0)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffff8000107960c0-ffff800010796134: acpi_rs_validate_parameters (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815fb14f)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff815fb14f-ffffffff815fb1a2: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815e667f)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff815e667f-ffffffff815e66d2: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816148b1)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff816148b1-ffffffff816149d7: acpi_rs_validate_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_rs_validate_parameters(acpi_handle device_handle, struct acpi_buffer *buffer, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8162e761)
Location: drivers/acpi/acpica/rsxface.c:57
Inline: False
Direct callers:
  - drivers/acpi/acpica/rsxface.c:acpi_get_event_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_possible_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_current_resources
  - drivers/acpi/acpica/rsxface.c:acpi_get_irq_routing_table
```
**Symbols:**

```
ffffffff8162e761-ffffffff8162e887: acpi_rs_validate_parameters (STB_LOCAL)
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
