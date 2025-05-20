# Function: <code>__print_tlp_header</code>

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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81449768)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81495d6a)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814b762c)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff814c1f69)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
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
In drivers/pci/pcie/aer/aerdrv_errprint.c (ffffffff81502180)
Location: drivers/pci/pcie/aer/aerdrv_errprint.c:132
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_errprint.c:cper_print_aer
  - drivers/pci/pcie/aer/aerdrv_errprint.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff815344f0)
Location: drivers/pci/pcie/aer.c:522
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:cper_print_aer
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
In drivers/pci/pcie/aer.c (ffffffff8154b9a9)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff8157bc7f)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff8159d6df)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __print_tlp_header(struct pci_dev *dev, struct aer_header_log_regs *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163cddb)
Location: drivers/pci/pcie/aer.c:643
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff8163cddb-ffffffff8163ce06: __print_tlp_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __print_tlp_header(struct pci_dev *dev, struct aer_header_log_regs *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81bf912c)
Location: drivers/pci/pcie/aer.c:663
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81bf912c-ffffffff81bf9157: __print_tlp_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __print_tlp_header(struct pci_dev *dev, struct aer_header_log_regs *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81beaf62)
Location: drivers/pci/pcie/aer.c:663
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81beaf62-ffffffff81beaf8d: __print_tlp_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __print_tlp_header(struct pci_dev *dev, struct aer_header_log_regs *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81ce5eb7)
Location: drivers/pci/pcie/aer.c:665
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81ce5eb7-ffffffff81ce5ee2: __print_tlp_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __print_tlp_header(struct pci_dev *dev, struct aer_header_log_regs *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81eac910)
Location: drivers/pci/pcie/aer.c:670
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
**Symbols:**

```
ffffffff81eac910-ffffffff81eac94d: __print_tlp_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff818fcceb)
Location: drivers/pci/pcie/aer.c:675
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8194019e)
Location: drivers/pci/pcie/aer.c:678
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff819889ee)
Location: drivers/pci/pcie/aer.c:667
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffff800010705834)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (c089c80c)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffe0004d35d0)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff81590e9b)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff815800af)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff8159142f)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
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
In drivers/pci/pcie/aer.c (ffffffff815ab8f4)
Location: drivers/pci/pcie/aer.c:710
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:cper_print_aer
  - drivers/pci/pcie/aer.c:aer_print_error
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
