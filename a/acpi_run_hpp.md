# Function: <code>acpi_run_hpp</code>

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
In drivers/pci/pci-acpi.c (ffffffff81457982)
Location: drivers/pci/pci-acpi.c:211
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
In drivers/pci/pci-acpi.c (ffffffff814a45c1)
Location: drivers/pci/pci-acpi.c:211
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
In drivers/pci/pci-acpi.c (ffffffff814c63d1)
Location: drivers/pci/pci-acpi.c:287
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
In drivers/pci/pci-acpi.c (ffffffff814d02ce)
Location: drivers/pci/pci-acpi.c:286
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
In drivers/pci/pci-acpi.c (ffffffff815104fd)
Location: drivers/pci/pci-acpi.c:286
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
In drivers/pci/pci-acpi.c (ffffffff8154579d)
Location: drivers/pci/pci-acpi.c:286
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
In drivers/pci/pci-acpi.c (ffffffff815417d8)
Location: drivers/pci/pci-acpi.c:286
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
In drivers/pci/pci-acpi.c (ffffffff815717a3)
Location: drivers/pci/pci-acpi.c:350
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
In drivers/pci/pci-acpi.c (ffffffff81592b40)
Location: drivers/pci/pci-acpi.c:699
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_run_hpp(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81640080)
Location: drivers/pci/pci-acpi.c:699
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81640080-ffffffff81640169: acpi_run_hpp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_run_hpp(struct pci_dev *dev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81666490)
Location: drivers/pci/pci-acpi.c:699
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
```
**Symbols:**

```
ffffffff81666490-ffffffff81666579: acpi_run_hpp (STB_LOCAL)
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
In drivers/pci/pci-acpi.c (ffffffff81649cee)
Location: drivers/pci/pci-acpi.c:699
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff816bb7be)
Location: drivers/pci/pci-acpi.c:700
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff817dfab0)
Location: drivers/pci/pci-acpi.c:700
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81902920)
Location: drivers/pci/pci-acpi.c:701
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff81945fb0)
Location: drivers/pci/pci-acpi.c:701
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffffffff8198f2e0)
Location: drivers/pci/pci-acpi.c:701
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
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
In drivers/pci/pci-acpi.c (ffff8000106f8ab4)
Location: drivers/pci/pci-acpi.c:699
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
In drivers/pci/pci-acpi.c (ffffffff815869d0)
Location: drivers/pci/pci-acpi.c:699
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
In drivers/pci/pci-acpi.c (ffffffff815757a0)
Location: drivers/pci/pci-acpi.c:699
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
In drivers/pci/pci-acpi.c (ffffffff81586890)
Location: drivers/pci/pci-acpi.c:699
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
In drivers/pci/pci-acpi.c (ffffffff815a0d40)
Location: drivers/pci/pci-acpi.c:699
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
</ul>
