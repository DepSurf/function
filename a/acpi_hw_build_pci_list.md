# Function: <code>acpi_hw_build_pci_list</code>

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
In drivers/acpi/acpica/hwpci.c (ffffffff8149a8a9)
Location: drivers/acpi/acpica/hwpci.c:172
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (ffffffff814e97a9)
Location: drivers/acpi/acpica/hwpci.c:172
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (ffffffff8150c031)
Location: drivers/acpi/acpica/hwpci.c:172
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (ffffffff8151c653)
Location: drivers/acpi/acpica/hwpci.c:172
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (ffffffff8156cbb4)
Location: drivers/acpi/acpica/hwpci.c:172
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_hw_build_pci_list(acpi_handle root_pci_device, acpi_handle pci_region, struct acpi_pci_device **return_list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff816bda06)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff816bda06-ffffffff816bdacb: acpi_hw_build_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_build_pci_list(acpi_handle root_pci_device, acpi_handle pci_region, struct acpi_pci_device **return_list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff816db5a8)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff816db5a8-ffffffff816db66d: acpi_hw_build_pci_list (STB_LOCAL)
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
In drivers/acpi/acpica/hwpci.c (ffffffff816bd56c)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (ffffffff817347fb)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (ffffffff8186580f)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_hw_build_pci_list(acpi_handle root_pci_device, acpi_handle pci_region, struct acpi_pci_device **return_list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff819a3910)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff819a3910-ffffffff819a3a06: acpi_hw_build_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_hw_build_pci_list(acpi_handle root_pci_device, acpi_handle pci_region, struct acpi_pci_device **return_list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff819ea5c0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff819ea5c0-ffffffff819ea6b6: acpi_hw_build_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_hw_build_pci_list(acpi_handle root_pci_device, acpi_handle pci_region, struct acpi_pci_device **return_list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff81a35340)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff81a35340-ffffffff81a35471: acpi_hw_build_pci_list (STB_LOCAL)
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
In drivers/acpi/acpica/hwpci.c (0)
Location: drivers/acpi/acpica/hwpci.c:136
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
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
