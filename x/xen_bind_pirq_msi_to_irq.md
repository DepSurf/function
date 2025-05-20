# Function: <code>xen_bind_pirq_msi_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9010)
Location: drivers/xen/events/events_base.c:729
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff814c9010-ffffffff814c916a: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519b20)
Location: drivers/xen/events/events_base.c:740
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81519b20-ffffffff81519c5e: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545ff0)
Location: drivers/xen/events/events_base.c:739
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81545ff0-ffffffff8154612e: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559e10)
Location: drivers/xen/events/events_base.c:731
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81559e10-ffffffff81559f50: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815be260)
Location: drivers/xen/events/events_base.c:731
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff815be260-ffffffff815be3a0: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f68a0)
Location: drivers/xen/events/events_base.c:729
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff815f68a0-ffffffff815f69e9: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611930)
Location: drivers/xen/events/events_base.c:729
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81611930-ffffffff81611a7b: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816456d0)
Location: drivers/xen/events/events_base.c:730
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff816456d0-ffffffff8164581d: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81667c70)
Location: drivers/xen/events/events_base.c:730
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81667c70-ffffffff81667dbd: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717dd0)
Location: drivers/xen/events/events_base.c:744
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81717dd0-ffffffff81717f6d: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735360)
Location: drivers/xen/events/events_base.c:1065
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81735360-ffffffff817354fd: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718970)
Location: drivers/xen/events/events_base.c:1102
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff81718970-ffffffff81718b0e: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817964b0)
Location: drivers/xen/events/events_base.c:1102
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff817964b0-ffffffff8179667e: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cf360)
Location: drivers/xen/events/events_base.c:1102
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff818cf360-ffffffff818cf539: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20a70)
Location: drivers/xen/events/events_base.c:1104
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff81a20a70-ffffffff81a20c49: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a69e00)
Location: drivers/xen/events/events_base.c:1097
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff81a69e00-ffffffff81a69fd9: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abc140)
Location: drivers/xen/events/events_base.c:1103
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_hvm_setup_msi_irqs
```
**Symbols:**

```
ffffffff81abc140-ffffffff81abc30e: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010831b80)
Location: drivers/xen/events/events_base.c:730
Inline: False
```
**Symbols:**

```
ffff800010831b80-ffff800010831d1c: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d9a0)
Location: drivers/xen/events/events_base.c:734
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff8162d9a0-ffffffff8162daed: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165bab0)
Location: drivers/xen/events/events_base.c:730
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff8165bab0-ffffffff8165bbfd: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_bind_pirq_msi_to_irq(struct pci_dev *dev, struct msi_desc *msidesc, int pirq, int nvec, const char *name, domid_t domid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816760a0)
Location: drivers/xen/events/events_base.c:730
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
**Symbols:**

```
ffffffff816760a0-ffffffff816761ed: xen_bind_pirq_msi_to_irq (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
