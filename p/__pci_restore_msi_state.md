# Function: <code>__pci_restore_msi_state</code>

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
In drivers/pci/msi.c (ffffffff81454de2)
Location: drivers/pci/msi.c:405
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff814a19f2)
Location: drivers/pci/msi.c:408
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff814c3642)
Location: drivers/pci/msi.c:408
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff814cdcd2)
Location: drivers/pci/msi.c:389
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8150e212)
Location: drivers/pci/msi.c:389
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff815430f2)
Location: drivers/pci/msi.c:389
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8155a492)
Location: drivers/pci/msi.c:389
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8158a594)
Location: drivers/pci/msi.c:411
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff815abf14)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff81655004)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8165eaf4)
Location: drivers/pci/msi.c:426
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff81640fe2)
Location: drivers/pci/msi.c:417
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff816b1c32)
Location: drivers/pci/msi.c:406
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi/msi.c (ffffffff817d5298)
Location: drivers/pci/msi/msi.c:261
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __pci_restore_msi_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f5720)
Location: drivers/pci/msi/msi.c:496
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff818f5720-ffffffff818f58a3: __pci_restore_msi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pci_restore_msi_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81938b50)
Location: drivers/pci/msi/msi.c:496
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff81938b50-ffffffff81938cd3: __pci_restore_msi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pci_restore_msi_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff819819b0)
Location: drivers/pci/msi/msi.c:497
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff819819b0-ffffffff81981b33: __pci_restore_msi_state (STB_GLOBAL)
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
In drivers/pci/msi.c (ffff8000107159a8)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c08a0330)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000885a00)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004df0dc)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
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
In drivers/pci/msi.c (ffffffff8159f6e4)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8158e874)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff8159fc64)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
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
In drivers/pci/msi.c (ffffffff815ba094)
Location: drivers/pci/msi.c:412
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
```
</details>
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
