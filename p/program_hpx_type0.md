# Function: <code>program_hpx_type0</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81591c20-ffffffff81591d30: program_hpx_type0 (STB_LOCAL)
ffffffff815931b6-ffffffff815931d5: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpp
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff8163ff70-ffffffff81640072: program_hpx_type0 (STB_LOCAL)
ffffffff81641644-ffffffff81641663: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_run_hpp
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81666380-ffffffff81666482: program_hpx_type0 (STB_LOCAL)
ffffffff81bf9fe7-ffffffff81bfa006: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81648920-ffffffff81648a22: program_hpx_type0 (STB_LOCAL)
ffffffff81bebe3e-ffffffff81bebe5d: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:138
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff816ba340-ffffffff816ba442: program_hpx_type0 (STB_LOCAL)
ffffffff81ce69fd-ffffffff81ce6a1c: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:138
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff817debc0-ffffffff817dece4: program_hpx_type0 (STB_LOCAL)
ffffffff81ead904-ffffffff81ead923: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81901870)
Location: drivers/pci/pci-acpi.c:139
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81901870-ffffffff819019aa: program_hpx_type0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81944e30)
Location: drivers/pci/pci-acpi.c:139
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff81944e30-ffffffff81944f6a: program_hpx_type0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198e160)
Location: drivers/pci/pci-acpi.c:139
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:acpi_run_hpx
```
**Symbols:**

```
ffffffff8198e160-ffffffff8198e29a: program_hpx_type0 (STB_LOCAL)
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
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffff8000106f7a40)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffff8000106f7a40-ffff8000106f7b74: program_hpx_type0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81585ab0-ffffffff81585bc0: program_hpx_type0 (STB_LOCAL)
ffffffff81587046-ffffffff81587065: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81574880-ffffffff81574990: program_hpx_type0 (STB_LOCAL)
ffffffff81575df6-ffffffff81575e15: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81585970-ffffffff81585a80: program_hpx_type0 (STB_LOCAL)
ffffffff81586f06-ffffffff81586f25: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void program_hpx_type0(struct pci_dev *dev, struct hpx_type0 *hpx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:137
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff8159fe20-ffffffff8159ff30: program_hpx_type0 (STB_LOCAL)
ffffffff815a13b6-ffffffff815a13d5: program_hpx_type0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
