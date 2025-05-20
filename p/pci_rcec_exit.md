# Function: <code>pci_rcec_exit</code>

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
void pci_rcec_exit(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff816605f0)
Location: drivers/pci/pcie/rcec.c:186
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff816605f0-ffffffff81660614: pci_rcec_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_rcec_exit(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff81642ad0)
Location: drivers/pci/pcie/rcec.c:186
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff81642ad0-ffffffff81642af4: pci_rcec_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_rcec_exit(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff816b37d0)
Location: drivers/pci/pcie/rcec.c:186
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff816b37d0-ffffffff816b37f4: pci_rcec_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_rcec_exit(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff817d6c40)
Location: drivers/pci/pcie/rcec.c:186
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff817d6c40-ffffffff817d6c6a: pci_rcec_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_rcec_exit(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff818f8230)
Location: drivers/pci/pcie/rcec.c:186
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff818f8230-ffffffff818f825a: pci_rcec_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_rcec_exit(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff8193b690)
Location: drivers/pci/pcie/rcec.c:186
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8193b690-ffffffff8193b6ba: pci_rcec_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_rcec_exit(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/rcec.c (ffffffff81984550)
Location: drivers/pci/pcie/rcec.c:186
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff81984550-ffffffff8198457a: pci_rcec_exit (STB_GLOBAL)
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
