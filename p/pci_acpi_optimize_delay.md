# Function: <code>pci_acpi_optimize_delay</code>

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
In drivers/pci/pci-acpi.c (ffffffff81457758)
Location: drivers/pci/pci-acpi.c:616
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff814a4381)
Location: drivers/pci/pci-acpi.c:616
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff814c6191)
Location: drivers/pci/pci-acpi.c:738
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff814d07bf)
Location: drivers/pci/pci-acpi.c:695
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff815109ef)
Location: drivers/pci/pci-acpi.c:695
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff81545ad3)
Location: drivers/pci/pci-acpi.c:736
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff81541b36)
Location: drivers/pci/pci-acpi.c:761
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff815711d6)
Location: drivers/pci/pci-acpi.c:839
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff81592586)
Location: drivers/pci/pci-acpi.c:1185
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_acpi_optimize_delay(struct pci_dev *pdev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81640600)
Location: drivers/pci/pci-acpi.c:1185
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81640600-ffffffff816406c8: pci_acpi_optimize_delay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_acpi_optimize_delay(struct pci_dev *pdev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81666a10)
Location: drivers/pci/pci-acpi.c:1215
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
```
**Symbols:**

```
ffffffff81666a10-ffffffff81666ad8: pci_acpi_optimize_delay (STB_LOCAL)
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
In drivers/pci/pci-acpi.c (ffffffff81649396)
Location: drivers/pci/pci-acpi.c:1215
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff816baef6)
Location: drivers/pci/pci-acpi.c:1311
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff817e04fb)
Location: drivers/pci/pci-acpi.c:1324
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff819034bb)
Location: drivers/pci/pci-acpi.c:1342
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff81946b5b)
Location: drivers/pci/pci-acpi.c:1369
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff8198fe8b)
Location: drivers/pci/pci-acpi.c:1369
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffff8000106f8390)
Location: drivers/pci/pci-acpi.c:1185
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff81586416)
Location: drivers/pci/pci-acpi.c:1185
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff815751e6)
Location: drivers/pci/pci-acpi.c:1185
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff815862d6)
Location: drivers/pci/pci-acpi.c:1185
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
In drivers/pci/pci-acpi.c (ffffffff815a0786)
Location: drivers/pci/pci-acpi.c:1185
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
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
