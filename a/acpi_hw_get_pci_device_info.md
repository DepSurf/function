# Function: <code>acpi_hw_get_pci_device_info</code>

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
In drivers/acpi/acpica/hwpci.c (ffffffff8149a93e)
Location: drivers/acpi/acpica/hwpci.c:332
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
In drivers/acpi/acpica/hwpci.c (ffffffff814e983c)
Location: drivers/acpi/acpica/hwpci.c:332
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
In drivers/acpi/acpica/hwpci.c (ffffffff8150c0c4)
Location: drivers/acpi/acpica/hwpci.c:332
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
In drivers/acpi/acpica/hwpci.c (ffffffff8151c6e9)
Location: drivers/acpi/acpica/hwpci.c:332
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
In drivers/acpi/acpica/hwpci.c (ffffffff8156ccc6)
Location: drivers/acpi/acpica/hwpci.c:332
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
In drivers/acpi/acpica/hwpci.c (ffffffff815a390e)
Location: drivers/acpi/acpica/hwpci.c:296
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
In drivers/acpi/acpica/hwpci.c (ffffffff815be419)
Location: drivers/acpi/acpica/hwpci.c:296
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
In drivers/acpi/acpica/hwpci.c (ffffffff815f002f)
Location: drivers/acpi/acpica/hwpci.c:296
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
In drivers/acpi/acpica/hwpci.c (ffffffff816114bd)
Location: drivers/acpi/acpica/hwpci.c:296
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
acpi_status acpi_hw_get_pci_device_info(struct acpi_pci_id *pci_id, acpi_handle pci_device, u16 *bus_number, u8 *is_bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff816bd77e)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
```
**Symbols:**

```
ffffffff816bd77e-ffffffff816bd8b6: acpi_hw_get_pci_device_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_get_pci_device_info(struct acpi_pci_id *pci_id, acpi_handle pci_device, u16 *bus_number, u8 *is_bridge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff816db320)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
```
**Symbols:**

```
ffffffff816db320-ffffffff816db458: acpi_hw_get_pci_device_info (STB_LOCAL)
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
In drivers/acpi/acpica/hwpci.c (ffffffff816bd34d)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
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
In drivers/acpi/acpica/hwpci.c (ffffffff817345dc)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
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
In drivers/acpi/acpica/hwpci.c (ffffffff818655e3)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
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
In drivers/acpi/acpica/hwpci.c (ffffffff819a36fa)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
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
In drivers/acpi/acpica/hwpci.c (ffffffff819ea3aa)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
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
In drivers/acpi/acpica/hwpci.c (ffffffff81a3512a)
Location: drivers/acpi/acpica/hwpci.c:296
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_process_pci_list
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
In drivers/acpi/acpica/hwpci.c (ffff80001078b95c)
Location: drivers/acpi/acpica/hwpci.c:296
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
In drivers/acpi/acpica/hwpci.c (ffffffff815f1dd9)
Location: drivers/acpi/acpica/hwpci.c:296
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
In drivers/acpi/acpica/hwpci.c (ffffffff815dd371)
Location: drivers/acpi/acpica/hwpci.c:296
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
In drivers/acpi/acpica/hwpci.c (ffffffff8160579d)
Location: drivers/acpi/acpica/hwpci.c:296
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
In drivers/acpi/acpica/hwpci.c (ffffffff8161f64d)
Location: drivers/acpi/acpica/hwpci.c:296
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
</ul>
