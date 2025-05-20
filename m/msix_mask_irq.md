# Function: <code>msix_mask_irq</code>

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
In drivers/pci/msi.c (ffffffff81454351)
Location: drivers/pci/msi.c:234
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff814a1a7b)
Location: drivers/pci/msi.c:240
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff814c36cb)
Location: drivers/pci/msi.c:240
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff814cce5a)
Location: drivers/pci/msi.c:221
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff8150d39a)
Location: drivers/pci/msi.c:221
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff81542293)
Location: drivers/pci/msi.c:221
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff8155a513)
Location: drivers/pci/msi.c:221
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void msix_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81588810)
Location: drivers/pci/msi.c:229
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff81588810-ffffffff81588852: msix_mask_irq (STB_LOCAL)
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
In drivers/pci/msi.c (ffffffff815abf9e)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff81654648)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
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
In drivers/pci/msi.c (ffffffff8165dd21)
Location: drivers/pci/msi.c:233
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
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
In drivers/pci/msi.c (ffffffff8164106c)
Location: drivers/pci/msi.c:204
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010715a10)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (c08a03ac)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (c000000000885a90)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffe0004df148)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff8159f76e)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff8158e8fe)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff8159fcee)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
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
In drivers/pci/msi.c (ffffffff815ba11e)
Location: drivers/pci/msi.c:230
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
