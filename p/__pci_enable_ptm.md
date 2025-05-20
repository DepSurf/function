# Function: <code>__pci_enable_ptm</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pci_enable_ptm(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff818ff580)
Location: drivers/pci/pcie/ptm.c:122
Inline: False
Direct callers:
  - drivers/pci/pcie/ptm.c:pci_resume_ptm
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
```
**Symbols:**

```
ffffffff818ff580-ffffffff818ff651: __pci_enable_ptm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pci_enable_ptm(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff81942af0)
Location: drivers/pci/pcie/ptm.c:122
Inline: False
Direct callers:
  - drivers/pci/pcie/ptm.c:pci_resume_ptm
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
```
**Symbols:**

```
ffffffff81942af0-ffffffff81942bc1: __pci_enable_ptm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pci_enable_ptm(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff8198bdc0)
Location: drivers/pci/pcie/ptm.c:123
Inline: False
Direct callers:
  - drivers/pci/pcie/ptm.c:pci_resume_ptm
  - drivers/pci/pcie/ptm.c:pci_enable_ptm
```
**Symbols:**

```
ffffffff8198bdc0-ffffffff8198be91: __pci_enable_ptm (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
