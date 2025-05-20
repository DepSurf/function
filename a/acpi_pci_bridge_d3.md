# Function: <code>acpi_pci_bridge_d3</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81541ca0)
Location: drivers/pci/pci-acpi.c:524
Inline: True
```
**Symbols:**

```
ffffffff81541ca0-ffffffff81541d74: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81571350)
Location: drivers/pci/pci-acpi.c:591
Inline: True
```
**Symbols:**

```
ffffffff81571350-ffffffff81571425: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81592700)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff81592700-ffffffff815927d5: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81641110)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff81641110-ffffffff81641207: acpi_pci_bridge_d3.part.0 (STB_LOCAL)
ffffffff81641210-ffffffff8164122c: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81667580)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff81667580-ffffffff816676fa: acpi_pci_bridge_d3.part.0 (STB_LOCAL)
ffffffff81667700-ffffffff8166771c: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81649a00)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff81649a00-ffffffff81649b84: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff816bb560)
Location: drivers/pci/pci-acpi.c:977
Inline: True
```
**Symbols:**

```
ffffffff816bb560-ffffffff816bb65d: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff817dfe00)
Location: drivers/pci/pci-acpi.c:975
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
```
**Symbols:**

```
ffffffff817dfe00-ffffffff817dff64: acpi_pci_bridge_d3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81902d20)
Location: drivers/pci/pci-acpi.c:976
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
```
**Symbols:**

```
ffffffff81902d20-ffffffff81902ead: acpi_pci_bridge_d3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff819463b0)
Location: drivers/pci/pci-acpi.c:976
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
```
**Symbols:**

```
ffffffff819463b0-ffffffff8194653d: acpi_pci_bridge_d3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198f6e0)
Location: drivers/pci/pci-acpi.c:976
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
```
**Symbols:**

```
ffffffff8198f6e0-ffffffff8198f86d: acpi_pci_bridge_d3 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffff8000106f8520)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffff8000106f8520-ffff8000106f8618: acpi_pci_bridge_d3 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81586590)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff81586590-ffffffff81586665: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81575360)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff81575360-ffffffff81575435: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81586450)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff81586450-ffffffff81586525: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool acpi_pci_bridge_d3(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff815a0900)
Location: drivers/pci/pci-acpi.c:937
Inline: True
```
**Symbols:**

```
ffffffff815a0900-ffffffff815a09d5: acpi_pci_bridge_d3 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
