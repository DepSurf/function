# Function: <code>pci_uevent_ers</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815218a0)
Location: drivers/pci/pci-driver.c:1549
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_nonfatal_recovery
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff815218a0-ffffffff81521937: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815376d0)
Location: drivers/pci/pci-driver.c:1546
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff815376d0-ffffffff81537767: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81567020)
Location: drivers/pci/pci-driver.c:1580
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff81567020-ffffffff815670b7: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81588380)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff81588380-ffffffff81588417: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162f000)
Location: drivers/pci/pci-driver.c:1558
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8162f000-ffffffff8162f097: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816546c0)
Location: drivers/pci/pci-driver.c:1537
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff816546c0-ffffffff81654757: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81637140)
Location: drivers/pci/pci-driver.c:1537
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff81637140-ffffffff816371d9: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a73b0)
Location: drivers/pci/pci-driver.c:1551
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff816a73b0-ffffffff816a7449: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff817c9d70)
Location: drivers/pci/pci-driver.c:1580
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff817c9d70-ffffffff817c9e2d: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff818e77c0)
Location: drivers/pci/pci-driver.c:1586
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff818e77c0-ffffffff818e787d: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8192ade0)
Location: drivers/pci/pci-driver.c:1587
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8192ade0-ffffffff8192ae9d: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81973670)
Location: drivers/pci/pci-driver.c:1600
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff81973670-ffffffff8197372d: pci_uevent_ers (STB_GLOBAL)
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
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106ec788)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffff8000106ec788-ffff8000106ec858: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0887a68)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
c0887a68-c0887b34: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0000000008684e0)
Location: drivers/pci/pci-driver.c:1593
Inline: False
```
**Symbols:**

```
c0000000008684e0-c0000000008685e4: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c17a0)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffe0004c17a0-ffffffe0004c1840: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157c210)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8157c210-ffffffff8157c2a7: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156afe0)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8156afe0-ffffffff8156b077: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157c0d0)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff8157c0d0-ffffffff8157c167: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_uevent_ers(struct pci_dev *pdev, enum pci_ers_result err_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81596580)
Location: drivers/pci/pci-driver.c:1593
Inline: False
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/err.c:report_resume
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
  - drivers/pci/pcie/err.c:report_error_detected
```
**Symbols:**

```
ffffffff81596580-ffffffff81596617: pci_uevent_ers (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
