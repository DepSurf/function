# Function: <code>pcie_pme_disable_interrupt</code>

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
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8157c560)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffffffff8157c560-ffffffff8157c5b4: pcie_pme_disable_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8159dfc0)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffffffff8159dfc0-ffffffff8159e014: pcie_pme_disable_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff8163db89)
Location: drivers/pci/pcie/pme.c:368
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81664219)
Location: drivers/pci/pcie/pme.c:376
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
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
In drivers/pci/pcie/pme.c (ffffffff81646689)
Location: drivers/pci/pcie/pme.c:376
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
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
In drivers/pci/pcie/pme.c (ffffffff816b7e89)
Location: drivers/pci/pcie/pme.c:376
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
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
In drivers/pci/pcie/pme.c (ffffffff817dc1c9)
Location: drivers/pci/pcie/pme.c:376
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
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
In drivers/pci/pcie/pme.c (ffffffff818fe0b9)
Location: drivers/pci/pcie/pme.c:376
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
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
In drivers/pci/pcie/pme.c (ffffffff81941569)
Location: drivers/pci/pcie/pme.c:376
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
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
In drivers/pci/pcie/pme.c (ffffffff8198a7c9)
Location: drivers/pci/pcie/pme.c:378
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
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
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffff800010705e38)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffff800010705e38-ffff800010705ee4: pcie_pme_disable_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (c089cb7c)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
c089cb7c-c089cbe4: pcie_pme_disable_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffe0004d3be0)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffffffe0004d3be0-ffffffe0004d3c74: pcie_pme_disable_interrupt (STB_LOCAL)
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
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff815917c0)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffffffff815917c0-ffffffff81591814: pcie_pme_disable_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff815806a0)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffffffff815806a0-ffffffff815806ee: pcie_pme_disable_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff81591d10)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffffffff81591d10-ffffffff81591d64: pcie_pme_disable_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcie_pme_disable_interrupt(struct pci_dev *port, struct pcie_pme_service_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pme.c (ffffffff815abbd0)
Location: drivers/pci/pcie/pme.c:368
Inline: False
Direct callers:
  - drivers/pci/pcie/pme.c:pcie_pme_remove
  - drivers/pci/pcie/pme.c:pcie_pme_suspend
```
**Symbols:**

```
ffffffff815abbd0-ffffffff815abc1b: pcie_pme_disable_interrupt (STB_LOCAL)
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
