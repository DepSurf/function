# Function: <code>pci_save_ptm_state</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_save_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/ptm.c (0)
Location: drivers/pci/pcie/ptm.c:49
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff81bf9f9b-ffffffff81bf9fb4: pci_save_ptm_state.cold (STB_LOCAL)
ffffffff81664dd0-ffffffff81664e21: pci_save_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_save_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/ptm.c (0)
Location: drivers/pci/pcie/ptm.c:49
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff81bebdf2-ffffffff81bebe0b: pci_save_ptm_state.cold (STB_LOCAL)
ffffffff81647380-ffffffff816473d1: pci_save_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_save_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff816b8c60)
Location: drivers/pci/pcie/ptm.c:49
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff816b8c60-ffffffff816b8cad: pci_save_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_save_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff817dd170)
Location: drivers/pci/pcie/ptm.c:49
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff817dd170-ffffffff817dd1d9: pci_save_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_save_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff818ff980)
Location: drivers/pci/pcie/ptm.c:87
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff818ff980-ffffffff818ff9e1: pci_save_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_save_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff81942ef0)
Location: drivers/pci/pcie/ptm.c:87
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff81942ef0-ffffffff81942f51: pci_save_ptm_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_save_ptm_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/ptm.c (ffffffff8198c1c0)
Location: drivers/pci/pcie/ptm.c:88
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff8198c1c0-ffffffff8198c221: pci_save_ptm_state (STB_GLOBAL)
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
