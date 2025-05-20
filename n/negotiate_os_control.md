# Function: <code>negotiate_os_control</code>

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
In drivers/acpi/pci_root.c (ffffffff81485ed9)
Location: drivers/acpi/pci_root.c:422
Inline: True
Inline callers:
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
In drivers/acpi/pci_root.c (ffffffff814d4a79)
Location: drivers/acpi/pci_root.c:422
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
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
In drivers/acpi/pci_root.c (ffffffff814f70c8)
Location: drivers/acpi/pci_root.c:422
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
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
In drivers/acpi/pci_root.c (ffffffff81505a4a)
Location: drivers/acpi/pci_root.c:422
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
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
In drivers/acpi/pci_root.c (ffffffff81547bc6)
Location: drivers/acpi/pci_root.c:423
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
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
In drivers/acpi/pci_root.c (ffffffff8157e054)
Location: drivers/acpi/pci_root.c:424
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
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
In drivers/acpi/pci_root.c (ffffffff81595d35)
Location: drivers/acpi/pci_root.c:424
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815c6d1b)
Location: drivers/acpi/pci_root.c:412
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff815c6d1b-ffffffff815c6fcd: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815e7f38)
Location: drivers/acpi/pci_root.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff815e7f38-ffffffff815e81ea: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff816938d4)
Location: drivers/acpi/pci_root.c:413
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff816938d4-ffffffff81693b3d: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81c0190d)
Location: drivers/acpi/pci_root.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81c0190d-ffffffff81c01b76: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81bf3336)
Location: drivers/acpi/pci_root.c:400
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81bf3336-ffffffff81bf3679: negotiate_os_control.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81ceff55)
Location: drivers/acpi/pci_root.c:402
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81ceff55-ffffffff81cf02d1: negotiate_os_control.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff81eb7de7)
Location: drivers/acpi/pci_root.c:613
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81eb7de7-ffffffff81eb8130: negotiate_os_control.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:564
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8196b5d0-ffffffff8196bde6: negotiate_os_control.constprop.0 (STB_LOCAL)
ffffffff82091b9e-ffffffff82091bd5: negotiate_os_control.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:564
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff819b1b50-ffffffff819b2358: negotiate_os_control.constprop.0 (STB_LOCAL)
ffffffff82112466-ffffffff8211249d: negotiate_os_control.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_root.c (0)
Location: drivers/acpi/pci_root.c:564
Inline: True
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff819fc030-ffffffff819fc838: negotiate_os_control.constprop.0 (STB_LOCAL)
ffffffff821f01ce-ffffffff821f0205: negotiate_os_control.constprop.0.cold (STB_LOCAL)
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
In drivers/acpi/pci_root.c (ffff800010774e68)
Location: drivers/acpi/pci_root.c:411
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
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
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815d9218)
Location: drivers/acpi/pci_root.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff815d9218-ffffffff815d94a3: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815c2e08)
Location: drivers/acpi/pci_root.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff815c2e08-ffffffff815c30ba: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815dc218)
Location: drivers/acpi/pci_root.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff815dc218-ffffffff815dc4ca: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void negotiate_os_control(struct acpi_pci_root *root, int *no_aspm, bool is_pcie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_root.c (ffffffff815f60d8)
Location: drivers/acpi/pci_root.c:411
Inline: False
Direct callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff815f60d8-ffffffff815f638a: negotiate_os_control (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
