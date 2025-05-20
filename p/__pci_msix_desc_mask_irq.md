# Function: <code>__pci_msix_desc_mask_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81454351)
Location: drivers/pci/msi.c:217
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_set_mask_bit
  - drivers/pci/msi.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff81454a20-ffffffff81454a5c: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1a7b)
Location: drivers/pci/msi.c:225
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff814a1630-ffffffff814a166e: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c36cb)
Location: drivers/pci/msi.c:225
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff814c3280-ffffffff814c32be: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cce5a)
Location: drivers/pci/msi.c:206
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff814cd950-ffffffff814cd98e: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150d39a)
Location: drivers/pci/msi.c:206
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff8150de90-ffffffff8150decd: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542293)
Location: drivers/pci/msi.c:206
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msix
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff81542d70-ffffffff81542dad: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8155a513)
Location: drivers/pci/msi.c:206
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff8155a120-ffffffff8155a15d: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81588815)
Location: drivers/pci/msi.c:209
Inline: True
```
**Symbols:**

```
ffffffff8158a1e0-ffffffff8158a227: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aaf26)
Location: drivers/pci/msi.c:209
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff815ab440-ffffffff815ab488: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81654648)
Location: drivers/pci/msi.c:209
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
```
**Symbols:**

```
ffffffff81654ca0-ffffffff81654ce8: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165dd21)
Location: drivers/pci/msi.c:212
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
**Symbols:**

```
ffffffff8165e790-ffffffff8165e7d8: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8164106c)
Location: drivers/pci/msi.c:183
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:__pci_write_msi_msg
  - drivers/pci/msi.c:pci_msi_unmask_irq
  - drivers/pci/msi.c:pci_msi_mask_irq
```
**Symbols:**

```
ffffffff81640c30-ffffffff81640c78: __pci_msix_desc_mask_irq (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010714670)
Location: drivers/pci/msi.c:209
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffff800010714bf8-ffff800010714c78: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089f594)
Location: drivers/pci/msi.c:209
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
c089f594-c089f604: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000884660)
Location: drivers/pci/msi.c:209
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
c000000000884660-c0000000008846d8: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004de522)
Location: drivers/pci/msi.c:209
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffe0004de522-ffffffe0004de5b4: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e6f6)
Location: drivers/pci/msi.c:209
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff8159ec10-ffffffff8159ec58: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158d886)
Location: drivers/pci/msi.c:209
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff8158dda0-ffffffff8158dde8: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159ec76)
Location: drivers/pci/msi.c:209
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff8159f190-ffffffff8159f1d8: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 __pci_msix_desc_mask_irq(struct msi_desc *desc, u32 flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b90a6)
Location: drivers/pci/msi.c:209
Inline: True
Direct callers:
  - drivers/pci/msi.c:pci_restore_msi_state
  - drivers/pci/msi.c:msi_set_mask_bit
```
**Symbols:**

```
ffffffff815b95c0-ffffffff815b9608: __pci_msix_desc_mask_irq (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
