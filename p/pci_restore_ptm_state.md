# Function: <code>pci_restore_ptm_state</code>

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
void pci_restore_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff81664e30)
Location: drivers/pci/pcie/ptm.c:72
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff81664e30-ffffffff81664e80: pci_restore_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_restore_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff816473e0)
Location: drivers/pci/pcie/ptm.c:72
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff816473e0-ffffffff81647430: pci_restore_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_restore_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff816b8cb0)
Location: drivers/pci/pcie/ptm.c:70
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff816b8cb0-ffffffff816b8d00: pci_restore_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_restore_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff817dd1e0)
Location: drivers/pci/pcie/ptm.c:70
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_finish_runtime_suspend
  - drivers/pci/pci.c:pci_prepare_to_sleep
```
**Symbols:**

```
ffffffff817dd1e0-ffffffff817dd24a: pci_restore_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_restore_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff818ffa00)
Location: drivers/pci/pcie/ptm.c:104
Inline: False
```
**Symbols:**

```
ffffffff818ffa00-ffffffff818ffa60: pci_restore_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_restore_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff81942f70)
Location: drivers/pci/pcie/ptm.c:104
Inline: False
```
**Symbols:**

```
ffffffff81942f70-ffffffff81942fd0: pci_restore_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_restore_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff8198c240)
Location: drivers/pci/pcie/ptm.c:105
Inline: False
```
**Symbols:**

```
ffffffff8198c240-ffffffff8198c2a0: pci_restore_ptm_state (STB_GLOBAL)
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
