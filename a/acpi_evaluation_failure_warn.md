# Function: <code>acpi_evaluation_failure_warn</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_evaluation_failure_warn(acpi_handle handle, const char *name, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682e40)
Location: drivers/acpi/utils.c:520
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff81682e40-ffffffff81682e7c: acpi_evaluation_failure_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_evaluation_failure_warn(acpi_handle handle, const char *name, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f7f90)
Location: drivers/acpi/utils.c:534
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff816f7f90-ffffffff816f7fcc: acpi_evaluation_failure_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_evaluation_failure_warn(acpi_handle handle, const char *name, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81824fb0)
Location: drivers/acpi/utils.c:534
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff81824fb0-ffffffff81824ffb: acpi_evaluation_failure_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_evaluation_failure_warn(acpi_handle handle, const char *name, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956150)
Location: drivers/acpi/utils.c:572
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff81956150-ffffffff8195619b: acpi_evaluation_failure_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_evaluation_failure_warn(acpi_handle handle, const char *name, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c550)
Location: drivers/acpi/utils.c:572
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff8199c550-ffffffff8199c59b: acpi_evaluation_failure_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_evaluation_failure_warn(acpi_handle handle, const char *name, acpi_status status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e5580)
Location: drivers/acpi/utils.c:644
Inline: False
Direct callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/processor_throttling.c:acpi_processor_get_tsd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
```
**Symbols:**

```
ffffffff819e5580-ffffffff819e55cb: acpi_evaluation_failure_warn (STB_GLOBAL)
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
