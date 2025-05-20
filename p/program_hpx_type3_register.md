# Function: <code>program_hpx_type3_register</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81559461)
Location: drivers/pci/probe.c:2122
Inline: True
Inline callers:
  - drivers/pci/probe.c:program_hpx_type3
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
In drivers/pci/pci-acpi.c (ffffffff81592293)
Location: drivers/pci/pci-acpi.c:497
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:497
Inline: False
```
**Symbols:**

```
ffffffff81640390-ffffffff81640540: program_hpx_type3_register (STB_LOCAL)
ffffffff8164167b-ffffffff81641694: program_hpx_type3_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:497
Inline: False
```
**Symbols:**

```
ffffffff816667a0-ffffffff81666950: program_hpx_type3_register (STB_LOCAL)
ffffffff81bfa01e-ffffffff81bfa037: program_hpx_type3_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:497
Inline: False
```
**Symbols:**

```
ffffffff81648c50-ffffffff81648e00: program_hpx_type3_register (STB_LOCAL)
ffffffff81bebe75-ffffffff81bebe8e: program_hpx_type3_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:498
Inline: False
```
**Symbols:**

```
ffffffff816ba670-ffffffff816ba848: program_hpx_type3_register (STB_LOCAL)
ffffffff81ce6a34-ffffffff81ce6a4c: program_hpx_type3_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:498
Inline: False
```
**Symbols:**

```
ffffffff817def20-ffffffff817df125: program_hpx_type3_register (STB_LOCAL)
ffffffff81ead93b-ffffffff81ead953: program_hpx_type3_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81901c30)
Location: drivers/pci/pci-acpi.c:499
Inline: False
```
**Symbols:**

```
ffffffff81901c30-ffffffff81901e69: program_hpx_type3_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff819451f0)
Location: drivers/pci/pci-acpi.c:499
Inline: False
```
**Symbols:**

```
ffffffff819451f0-ffffffff81945423: program_hpx_type3_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void program_hpx_type3_register(struct pci_dev *dev, const struct hpx_type3 *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198e520)
Location: drivers/pci/pci-acpi.c:499
Inline: False
```
**Symbols:**

```
ffffffff8198e520-ffffffff8198e753: program_hpx_type3_register (STB_LOCAL)
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
In drivers/pci/pci-acpi.c (ffff8000106f809c)
Location: drivers/pci/pci-acpi.c:497
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff81586123)
Location: drivers/pci/pci-acpi.c:497
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff81574ef3)
Location: drivers/pci/pci-acpi.c:497
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff81585fe3)
Location: drivers/pci/pci-acpi.c:497
Inline: True
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
In drivers/pci/pci-acpi.c (ffffffff815a0493)
Location: drivers/pci/pci-acpi.c:497
Inline: True
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
