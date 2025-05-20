# Function: <code>__pcie_print_link_status</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534f00)
Location: drivers/pci/pci.c:5641
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81534f00-ffffffff815350f9: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:5737
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81564ddb-ffffffff81564f77: __pcie_print_link_status.cold (STB_LOCAL)
ffffffff815643c0-ffffffff81564446: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff815860cd-ffffffff81586285: __pcie_print_link_status.cold (STB_LOCAL)
ffffffff815856a0-ffffffff8158572f: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c210)
Location: drivers/pci/pci.c:5888
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff8162c210-ffffffff8162c377: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651f70)
Location: drivers/pci/pci.c:5962
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81651f70-ffffffff816520d7: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634a20)
Location: drivers/pci/pci.c:6011
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81634a20-ffffffff81634b87: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4b10)
Location: drivers/pci/pci.c:6201
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff816a4b10-ffffffff816a4c77: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c6fa0)
Location: drivers/pci/pci.c:6297
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff817c6fa0-ffffffff817c712c: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e4460)
Location: drivers/pci/pci.c:6244
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff818e4460-ffffffff818e4612: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927ab0)
Location: drivers/pci/pci.c:6366
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81927ab0-ffffffff81927c62: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81970250)
Location: drivers/pci/pci.c:6510
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81970250-ffffffff81970402: __pcie_print_link_status (STB_GLOBAL)
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
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e9e20)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffff8000106e9e20-ffff8000106ea050: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884d90)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
c0884d90-c0884ffc: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864fd0)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
c000000000864fd0-c00000000086526c: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004c0088)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffe0004c0088-ffffffe0004c0252: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff8157a5ed-ffffffff8157a7a5: __pcie_print_link_status.cold (STB_LOCAL)
ffffffff81579bc0-ffffffff81579c4f: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81568d2d-ffffffff81568ee5: __pcie_print_link_status.cold (STB_LOCAL)
ffffffff81568300-ffffffff8156838f: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff81579e1d-ffffffff81579fd5: __pcie_print_link_status.cold (STB_LOCAL)
ffffffff815793f0-ffffffff8157947f: __pcie_print_link_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __pcie_print_link_status(struct pci_dev *dev, bool verbose);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:5867
Inline: False
Direct callers:
  - drivers/pci/pci.c:pcie_print_link_status
```
**Symbols:**

```
ffffffff815942cd-ffffffff81594485: __pcie_print_link_status.cold (STB_LOCAL)
ffffffff81593880-ffffffff8159390f: __pcie_print_link_status (STB_GLOBAL)
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
