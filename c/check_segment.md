# Function: <code>check_segment</code>

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
In arch/x86/pci/acpi.c (ffffffff816f8d1c)
Location: arch/x86/pci/acpi.c:157
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8175da2c)
Location: arch/x86/pci/acpi.c:157
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff81789f5c)
Location: arch/x86/pci/acpi.c:167
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff817a909c)
Location: arch/x86/pci/acpi.c:167
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8182054c)
Location: arch/x86/pci/acpi.c:168
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8186a7fe)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8188a8ce)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff818d539c)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8190771c)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_segment(u16 seg, struct device *dev, char *estr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff81bb7dd9)
Location: arch/x86/pci/acpi.c:166
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:setup_mcfg_map
  - arch/x86/pci/acpi.c:setup_mcfg_map
```
**Symbols:**

```
ffffffff81bb7dd9-ffffffff81bb7e11: check_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_segment(u16 seg, struct device *dev, char *estr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff81c345c6)
Location: arch/x86/pci/acpi.c:166
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:setup_mcfg_map
  - arch/x86/pci/acpi.c:setup_mcfg_map
```
**Symbols:**

```
ffffffff81c345c6-ffffffff81c345fe: check_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_segment(u16 seg, struct device *dev, char *estr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff81c269a2)
Location: arch/x86/pci/acpi.c:166
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81c269a2-ffffffff81c269da: check_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_segment(u16 seg, struct device *dev, char *estr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff81d447f9)
Location: arch/x86/pci/acpi.c:166
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81d447f9-ffffffff81d44831: check_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_segment(u16 seg, struct device *dev, char *estr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/acpi.c (ffffffff81f11704)
Location: arch/x86/pci/acpi.c:252
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
```
**Symbols:**

```
ffffffff81f11704-ffffffff81f11744: check_segment (STB_LOCAL)
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
In arch/x86/pci/acpi.c (ffffffff82019255)
Location: arch/x86/pci/acpi.c:254
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff820998d5)
Location: arch/x86/pci/acpi.c:254
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff82170f9d)
Location: arch/x86/pci/acpi.c:254
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff818a6adc)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff818615fc)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff818f813c)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
In arch/x86/pci/acpi.c (ffffffff8191923c)
Location: arch/x86/pci/acpi.c:166
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_root_init_info
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
