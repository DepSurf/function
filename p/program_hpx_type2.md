# Function: <code>program_hpx_type2</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81592cd7)
Location: drivers/pci/pci-acpi.c:283
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:283
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81640170-ffffffff81640381: program_hpx_type2 (STB_LOCAL)
ffffffff81641663-ffffffff8164167b: program_hpx_type2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:283
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81666580-ffffffff81666793: program_hpx_type2 (STB_LOCAL)
ffffffff81bfa006-ffffffff81bfa01e: program_hpx_type2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:283
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81648a30-ffffffff81648c43: program_hpx_type2 (STB_LOCAL)
ffffffff81bebe5d-ffffffff81bebe75: program_hpx_type2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:284
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff816ba450-ffffffff816ba662: program_hpx_type2 (STB_LOCAL)
ffffffff81ce6a1c-ffffffff81ce6a34: program_hpx_type2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:284
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff817decf0-ffffffff817def18: program_hpx_type2 (STB_LOCAL)
ffffffff81ead923-ffffffff81ead93b: program_hpx_type2.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff819019c0)
Location: drivers/pci/pci-acpi.c:285
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff819019c0-ffffffff81901c1f: program_hpx_type2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81944f80)
Location: drivers/pci/pci-acpi.c:285
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81944f80-ffffffff819451df: program_hpx_type2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void program_hpx_type2(struct pci_dev *dev, struct hpx_type2 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198e2b0)
Location: drivers/pci/pci-acpi.c:285
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff8198e2b0-ffffffff8198e50f: program_hpx_type2 (STB_LOCAL)
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
In drivers/pci/pci-acpi.c (ffff8000106f8c94)
Location: drivers/pci/pci-acpi.c:283
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81586b67)
Location: drivers/pci/pci-acpi.c:283
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81575937)
Location: drivers/pci/pci-acpi.c:283
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81586a27)
Location: drivers/pci/pci-acpi.c:283
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff815a0ed7)
Location: drivers/pci/pci-acpi.c:283
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
