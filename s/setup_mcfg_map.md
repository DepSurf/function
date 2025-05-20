# Function: <code>setup_mcfg_map</code>

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
In arch/x86/pci/acpi.c (ffffffff816f8ce6)
Location: arch/x86/pci/acpi.c:180
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8175d9f6)
Location: arch/x86/pci/acpi.c:180
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81789f26)
Location: arch/x86/pci/acpi.c:190
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff817a9066)
Location: arch/x86/pci/acpi.c:190
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81820516)
Location: arch/x86/pci/acpi.c:191
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8186a755)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8188a825)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff818d50a5)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81907425)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int setup_mcfg_map(struct acpi_pci_root_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:189
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81bb7a40-ffffffff81bb7ae6: setup_mcfg_map (STB_LOCAL)
ffffffff81bb7e11-ffffffff81bb7e3f: setup_mcfg_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int setup_mcfg_map(struct acpi_pci_root_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/acpi.c (0)
Location: arch/x86/pci/acpi.c:189
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81bcc790-ffffffff81bcc836: setup_mcfg_map (STB_LOCAL)
ffffffff81c345fe-ffffffff81c3462c: setup_mcfg_map.cold (STB_LOCAL)
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
In arch/x86/pci/acpi.c (ffffffff81bc01d5)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81c90115)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81e3f215)
Location: arch/x86/pci/acpi.c:275
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff820191c5)
Location: arch/x86/pci/acpi.c:273
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff82099845)
Location: arch/x86/pci/acpi.c:273
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff82170ef5)
Location: arch/x86/pci/acpi.c:273
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff818a67e5)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81861315)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff818f7e45)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81918f45)
Location: arch/x86/pci/acpi.c:189
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
