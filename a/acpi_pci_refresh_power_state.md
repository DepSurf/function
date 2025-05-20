# Function: <code>acpi_pci_refresh_power_state</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81570d20)
Location: drivers/pci/pci-acpi.c:695
Inline: False
```
**Symbols:**

```
ffffffff81570d20-ffffffff81570d59: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81591f10)
Location: drivers/pci/pci-acpi.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81591f10-ffffffff81591f49: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81640800)
Location: drivers/pci/pci-acpi.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81640800-ffffffff8164083f: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81666c10)
Location: drivers/pci/pci-acpi.c:1051
Inline: False
```
**Symbols:**

```
ffffffff81666c10-ffffffff81666c52: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81648ff0)
Location: drivers/pci/pci-acpi.c:1051
Inline: False
```
**Symbols:**

```
ffffffff81648ff0-ffffffff81649032: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff816baad0)
Location: drivers/pci/pci-acpi.c:1071
Inline: False
```
**Symbols:**

```
ffffffff816baad0-ffffffff816bab12: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff817e0140)
Location: drivers/pci/pci-acpi.c:1088
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_refresh_power_state
```
**Symbols:**

```
ffffffff817e0140-ffffffff817e0196: acpi_pci_refresh_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff819030b0)
Location: drivers/pci/pci-acpi.c:1106
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_refresh_power_state
```
**Symbols:**

```
ffffffff819030b0-ffffffff81903103: acpi_pci_refresh_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81946750)
Location: drivers/pci/pci-acpi.c:1133
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_refresh_power_state
```
**Symbols:**

```
ffffffff81946750-ffffffff819467a3: acpi_pci_refresh_power_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff8198fa80)
Location: drivers/pci/pci-acpi.c:1133
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_refresh_power_state
```
**Symbols:**

```
ffffffff8198fa80-ffffffff8198fad3: acpi_pci_refresh_power_state (STB_GLOBAL)
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
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffff8000106f7c98)
Location: drivers/pci/pci-acpi.c:1041
Inline: False
```
**Symbols:**

```
ffff8000106f7c98-ffff8000106f7cf4: acpi_pci_refresh_power_state (STB_LOCAL)
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
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81585da0)
Location: drivers/pci/pci-acpi.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81585da0-ffffffff81585dd9: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81574b70)
Location: drivers/pci/pci-acpi.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81574b70-ffffffff81574ba9: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81585c60)
Location: drivers/pci/pci-acpi.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81585c60-ffffffff81585c99: acpi_pci_refresh_power_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_pci_refresh_power_state(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff815a0110)
Location: drivers/pci/pci-acpi.c:1041
Inline: False
```
**Symbols:**

```
ffffffff815a0110-ffffffff815a0149: acpi_pci_refresh_power_state (STB_LOCAL)
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
