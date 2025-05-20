# Function: <code>pci_msi_update_mask</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_msi_update_mask(struct msi_desc *desc, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b01b0)
Location: drivers/pci/msi.c:146
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
**Symbols:**

```
ffffffff816b01b0-ffffffff816b0225: pci_msi_update_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_msi_update_mask(struct msi_desc *desc, u32 clear, u32 set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d37e0)
Location: drivers/pci/msi/msi.c:19
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:pci_restore_msi_state
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
```
**Symbols:**

```
ffffffff817d37e0-ffffffff817d3869: pci_msi_update_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_update_mask(struct msi_desc *desc, u32 clear, u32 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f5802)
Location: drivers/pci/msi/msi.c:110
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
Direct callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
```
**Symbols:**

```
ffffffff818f4d90-ffffffff818f4e19: pci_msi_update_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_update_mask(struct msi_desc *desc, u32 clear, u32 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81938c32)
Location: drivers/pci/msi/msi.c:110
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
Direct callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
```
**Symbols:**

```
ffffffff819381c0-ffffffff81938249: pci_msi_update_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_msi_update_mask(struct msi_desc *desc, u32 clear, u32 set);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81981a92)
Location: drivers/pci/msi/msi.c:111
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_restore_msi_state
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_mask_irq
Direct callers:
  - drivers/pci/msi/msi.c:pci_msi_shutdown
  - drivers/pci/msi/msi.c:msi_capability_init
  - drivers/pci/msi/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi/irqdomain.c:pci_irq_unmask_msi
  - drivers/pci/msi/irqdomain.c:pci_irq_mask_msi
```
**Symbols:**

```
ffffffff81981020-ffffffff819810a9: pci_msi_update_mask (STB_GLOBAL)
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
