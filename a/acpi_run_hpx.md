# Function: <code>acpi_run_hpx</code>

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
In drivers/pci/pci-acpi.c (ffffffff81457959)
Location: drivers/pci/pci-acpi.c:147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff814a45a1)
Location: drivers/pci/pci-acpi.c:147
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff814c63b1)
Location: drivers/pci/pci-acpi.c:223
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff814d02b6)
Location: drivers/pci/pci-acpi.c:222
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff815104e5)
Location: drivers/pci/pci-acpi.c:222
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81545664)
Location: drivers/pci/pci-acpi.c:222
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff8154169f)
Location: drivers/pci/pci-acpi.c:222
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff815715a1)
Location: drivers/pci/pci-acpi.c:274
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81592942)
Location: drivers/pci/pci-acpi.c:624
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
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:624
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81640d70-ffffffff8164110a: acpi_run_hpx (STB_LOCAL)
ffffffff816416b2-ffffffff81641758: acpi_run_hpx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:624
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff816671e0-ffffffff8166757a: acpi_run_hpx (STB_LOCAL)
ffffffff81bfa055-ffffffff81bfa0fb: acpi_run_hpx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:624
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81649680-ffffffff816499fa: acpi_run_hpx (STB_LOCAL)
ffffffff81bebeae-ffffffff81bebf54: acpi_run_hpx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:625
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff816bb1e0-ffffffff816bb55a: acpi_run_hpx (STB_LOCAL)
ffffffff81ce6a6c-ffffffff81ce6b12: acpi_run_hpx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:625
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff817df560-ffffffff817df930: acpi_run_hpx (STB_LOCAL)
ffffffff81ead972-ffffffff81eada17: acpi_run_hpx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81902330)
Location: drivers/pci/pci-acpi.c:626
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81902330-ffffffff8190277a: acpi_run_hpx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff819459c0)
Location: drivers/pci/pci-acpi.c:626
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff819459c0-ffffffff81945e0a: acpi_run_hpx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_run_hpx(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198ecf0)
Location: drivers/pci/pci-acpi.c:626
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff8198ecf0-ffffffff8198f13a: acpi_run_hpx (STB_LOCAL)
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
In drivers/pci/pci-acpi.c (ffff8000106f88d8)
Location: drivers/pci/pci-acpi.c:624
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
In drivers/pci/pci-acpi.c (ffffffff815867d2)
Location: drivers/pci/pci-acpi.c:624
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
In drivers/pci/pci-acpi.c (ffffffff815755a2)
Location: drivers/pci/pci-acpi.c:624
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
In drivers/pci/pci-acpi.c (ffffffff81586692)
Location: drivers/pci/pci-acpi.c:624
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
In drivers/pci/pci-acpi.c (ffffffff815a0b42)
Location: drivers/pci/pci-acpi.c:624
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
