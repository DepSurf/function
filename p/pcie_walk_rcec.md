# Function: <code>pcie_walk_rcec</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcie_walk_rcec(struct pci_dev *rcec, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff816604a0)
Location: drivers/pci/pcie/rcec.c:134
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff816604a0-ffffffff816604f5: pcie_walk_rcec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcie_walk_rcec(struct pci_dev *rcec, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff81642980)
Location: drivers/pci/pcie/rcec.c:134
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff81642980-ffffffff816429d5: pcie_walk_rcec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcie_walk_rcec(struct pci_dev *rcec, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff816b3680)
Location: drivers/pci/pcie/rcec.c:134
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff816b3680-ffffffff816b36d5: pcie_walk_rcec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcie_walk_rcec(struct pci_dev *rcec, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff817d6ad0)
Location: drivers/pci/pcie/rcec.c:134
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff817d6ad0-ffffffff817d6b31: pcie_walk_rcec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcie_walk_rcec(struct pci_dev *rcec, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff818f80a0)
Location: drivers/pci/pcie/rcec.c:134
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff818f80a0-ffffffff818f8101: pcie_walk_rcec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcie_walk_rcec(struct pci_dev *rcec, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff8193b500)
Location: drivers/pci/pcie/rcec.c:134
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff8193b500-ffffffff8193b561: pcie_walk_rcec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcie_walk_rcec(struct pci_dev *rcec, int (*cb)(struct pci_dev *, void *), void *userdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff81984390)
Location: drivers/pci/pcie/rcec.c:134
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:find_source_device
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
**Symbols:**

```
ffffffff81984390-ffffffff819843f1: pcie_walk_rcec (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
