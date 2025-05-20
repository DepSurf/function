# Function: <code>__pci_dev_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __pci_dev_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81438210)
Location: drivers/pci/pci.c:3605
Inline: True
Direct callers:
  - drivers/pci/pci.c:__pci_reset_function_locked
  - drivers/pci/pci.c:__pci_reset_function
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81438210-ffffffff81438555: __pci_dev_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __pci_dev_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81483eb0)
Location: drivers/pci/pci.c:3926
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:__pci_reset_function_locked
  - drivers/pci/pci.c:__pci_reset_function
```
**Symbols:**

```
ffffffff81483eb0-ffffffff81484208: __pci_dev_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __pci_dev_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5610)
Location: drivers/pci/pci.c:3964
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:__pci_reset_function_locked
  - drivers/pci/pci.c:__pci_reset_function
```
**Symbols:**

```
ffffffff814a5610-ffffffff814a5968: __pci_dev_reset (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
