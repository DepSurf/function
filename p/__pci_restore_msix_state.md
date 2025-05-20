# Function: <code>__pci_restore_msix_state</code>

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
In drivers/pci/msi.c (ffffffff81454df1)
Location: drivers/pci/msi.c:427
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
In drivers/pci/msi.c (ffffffff814a1a01)
Location: drivers/pci/msi.c:430
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
In drivers/pci/msi.c (ffffffff814c3651)
Location: drivers/pci/msi.c:430
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
In drivers/pci/msi.c (ffffffff814cdce1)
Location: drivers/pci/msi.c:411
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
In drivers/pci/msi.c (ffffffff8150e221)
Location: drivers/pci/msi.c:411
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
In drivers/pci/msi.c (ffffffff81543101)
Location: drivers/pci/msi.c:411
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
In drivers/pci/msi.c (ffffffff8155a4a1)
Location: drivers/pci/msi.c:411
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
In drivers/pci/msi.c (ffffffff8158a5a3)
Location: drivers/pci/msi.c:433
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
In drivers/pci/msi.c (ffffffff815abf23)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (ffffffff81655013)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (ffffffff8165eb03)
Location: drivers/pci/msi.c:458
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
In drivers/pci/msi.c (ffffffff81640ff1)
Location: drivers/pci/msi.c:449
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
In drivers/pci/msi.c (ffffffff816b1c41)
Location: drivers/pci/msi.c:437
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
In drivers/pci/msi/msi.c (ffffffff817d52a7)
Location: drivers/pci/msi/msi.c:293
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
void __pci_restore_msix_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f6170)
Location: drivers/pci/msi/msi.c:843
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff818f6170-ffffffff818f62df: __pci_restore_msix_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pci_restore_msix_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff819395d0)
Location: drivers/pci/msi/msi.c:838
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff819395d0-ffffffff8193973f: __pci_restore_msix_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pci_restore_msix_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81982430)
Location: drivers/pci/msi/msi.c:840
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff81982430-ffffffff8198259f: __pci_restore_msix_state (STB_GLOBAL)
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
In drivers/pci/msi.c (ffff8000107159ac)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (c08a0340)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (c000000000885a10)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (ffffffe0004df0e6)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (ffffffff8159f6f3)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (ffffffff8158e883)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (ffffffff8159fc73)
Location: drivers/pci/msi.c:434
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
In drivers/pci/msi.c (ffffffff815ba0a3)
Location: drivers/pci/msi.c:434
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
