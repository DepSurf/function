# Function: <code>acpi_pci_query_osc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814859f8)
Location: drivers/acpi/pci_root.c:206
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff814d4b2e)
Location: drivers/acpi/pci_root.c:206
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff814f717d)
Location: drivers/acpi/pci_root.c:206
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff81505b82)
Location: drivers/acpi/pci_root.c:206
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff81547cdc)
Location: drivers/acpi/pci_root.c:207
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff8157e141)
Location: drivers/acpi/pci_root.c:208
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff81595e3b)
Location: drivers/acpi/pci_root.c:208
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815c6dd2)
Location: drivers/acpi/pci_root.c:196
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815e7fef)
Location: drivers/acpi/pci_root.c:195
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_pci_query_osc(struct acpi_pci_root *root, u32 support, u32 *control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81692d50)
Location: drivers/acpi/pci_root.c:197
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
```
**Symbols:**

```
ffffffff81692d50-ffffffff81692e98: acpi_pci_query_osc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_pci_query_osc(struct acpi_pci_root *root, u32 support, u32 *control);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff816b0820)
Location: drivers/acpi/pci_root.c:195
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
```
**Symbols:**

```
ffffffff816b0820-ffffffff816b0968: acpi_pci_query_osc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_pci_query_osc(struct acpi_pci_root *root, u32 support, u32 *control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81bf31c4)
Location: drivers/acpi/pci_root.c:193
Inline: True
```
**Symbols:**

```
ffffffff81bf31c4-ffffffff81bf3261: acpi_pci_query_osc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_pci_query_osc(struct acpi_pci_root *root, u32 support, u32 *control);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81cefde3)
Location: drivers/acpi/pci_root.c:195
Inline: True
```
**Symbols:**

```
ffffffff81cefde3-ffffffff81cefe80: acpi_pci_query_osc (STB_LOCAL)
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
In drivers/acpi/pci_root.c (ffffffff81eb7bae)
Location: drivers/acpi/pci_root.c:243
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff8196b0c6)
Location: drivers/acpi/pci_root.c:243
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff819b1673)
Location: drivers/acpi/pci_root.c:243
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff819fbb53)
Location: drivers/acpi/pci_root.c:243
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffff800010774ed4)
Location: drivers/acpi/pci_root.c:195
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815d92cf)
Location: drivers/acpi/pci_root.c:195
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815c2ebf)
Location: drivers/acpi/pci_root.c:195
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815dc2cf)
Location: drivers/acpi/pci_root.c:195
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
In drivers/acpi/pci_root.c (ffffffff815f618f)
Location: drivers/acpi/pci_root.c:195
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:negotiate_os_control
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
