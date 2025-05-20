# Function: <code>acpi_hw_process_pci_list</code>

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
In drivers/acpi/acpica/hwpci.c (ffffffff8149a921)
Location: drivers/acpi/acpica/hwpci.c:241
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
In drivers/acpi/acpica/hwpci.c (ffffffff814e9819)
Location: drivers/acpi/acpica/hwpci.c:241
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
In drivers/acpi/acpica/hwpci.c (ffffffff8150c0a1)
Location: drivers/acpi/acpica/hwpci.c:241
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
In drivers/acpi/acpica/hwpci.c (ffffffff8151c6c6)
Location: drivers/acpi/acpica/hwpci.c:241
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
In drivers/acpi/acpica/hwpci.c (ffffffff8156cc23)
Location: drivers/acpi/acpica/hwpci.c:241
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
In drivers/acpi/acpica/hwpci.c (ffffffff815a386b)
Location: drivers/acpi/acpica/hwpci.c:205
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
In drivers/acpi/acpica/hwpci.c (ffffffff815be3ac)
Location: drivers/acpi/acpica/hwpci.c:205
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
In drivers/acpi/acpica/hwpci.c (ffffffff815effc0)
Location: drivers/acpi/acpica/hwpci.c:205
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
In drivers/acpi/acpica/hwpci.c (ffffffff8161144e)
Location: drivers/acpi/acpica/hwpci.c:205
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
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff816bd8b6)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff816bd8b6-ffffffff816bd9e2: acpi_hw_process_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff816db458)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff816db458-ffffffff816db584: acpi_hw_process_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff816bd2b7)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff816bd2b7-ffffffff816bd4c9: acpi_hw_process_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff81734546)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff81734546-ffffffff81734758: acpi_hw_process_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff8186554d)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff8186554d-ffffffff81865764: acpi_hw_process_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff819a3680)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff819a3680-ffffffff819a38f3: acpi_hw_process_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff819ea330)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff819ea330-ffffffff819ea5a3: acpi_hw_process_pci_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_hw_process_pci_list(struct acpi_pci_id *pci_id, struct acpi_pci_device *list_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwpci.c (ffffffff81a350b0)
Location: drivers/acpi/acpica/hwpci.c:205
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff81a350b0-ffffffff81a35323: acpi_hw_process_pci_list (STB_LOCAL)
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
In drivers/acpi/acpica/hwpci.c (ffff80001078b940)
Location: drivers/acpi/acpica/hwpci.c:205
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
In drivers/acpi/acpica/hwpci.c (ffffffff815f1e11)
Location: drivers/acpi/acpica/hwpci.c:205
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
In drivers/acpi/acpica/hwpci.c (ffffffff815dd3a9)
Location: drivers/acpi/acpica/hwpci.c:205
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
In drivers/acpi/acpica/hwpci.c (ffffffff8160572e)
Location: drivers/acpi/acpica/hwpci.c:205
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
In drivers/acpi/acpica/hwpci.c (ffffffff8161f5de)
Location: drivers/acpi/acpica/hwpci.c:205
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
