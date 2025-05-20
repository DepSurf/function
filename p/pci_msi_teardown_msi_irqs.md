# Function: <code>pci_msi_teardown_msi_irqs</code>

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
In drivers/pci/msi.c (ffffffff814540e9)
Location: drivers/pci/msi.c:63
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff814a0a0f)
Location: drivers/pci/msi.c:65
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff814c269c)
Location: drivers/pci/msi.c:65
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff814ccb66)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff8150d09f)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff81541f8f)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff815592df)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff8158939f)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff815aad3f)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff81653c1b)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff8165d08b)
Location: drivers/pci/msi.c:48
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff8163f62b)
Location: drivers/pci/msi.c:48
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff816b04de)
Location: drivers/pci/msi.c:48
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_msi_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff817d5800)
Location: drivers/pci/msi/irqdomain.c:22
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff817d5800-ffffffff817d5857: pci_msi_teardown_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_msi_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff818f6a10)
Location: drivers/pci/msi/irqdomain.c:22
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff818f6a10-ffffffff818f6a69: pci_msi_teardown_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_msi_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff81939e70)
Location: drivers/pci/msi/irqdomain.c:22
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81939e70-ffffffff81939ed0: pci_msi_teardown_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_msi_teardown_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/irqdomain.c (ffffffff81982cd0)
Location: drivers/pci/msi/irqdomain.c:22
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81982cd0-ffffffff81982d30: pci_msi_teardown_msi_irqs (STB_GLOBAL)
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
In drivers/pci/msi.c (ffff800010714480)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (c089ee7c)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004de01c)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff8159e50f)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff8158d69f)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff8159ea8f)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/msi.c (ffffffff815b8ebf)
Location: drivers/pci/msi.c:46
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
