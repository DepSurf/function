# Function: <code>default_restore_msi_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81454cd0)
Location: drivers/pci/msi.c:153
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff81454cd0-ffffffff81454d33: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a18e0)
Location: drivers/pci/msi.c:155
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff814a18e0-ffffffff814a194d: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c3530)
Location: drivers/pci/msi.c:155
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff814c3530-ffffffff814c359d: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cdbc0)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff814cdbc0-ffffffff814cdc2d: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150e100)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8150e100-ffffffff8150e16d: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542fe0)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff81542fe0-ffffffff8154304d: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8155a380)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8155a380-ffffffff8155a3ed: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158a480)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8158a480-ffffffff8158a4ee: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815abe00)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff815abe00-ffffffff815abe6e: default_restore_msi_irq (STB_LOCAL)
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
In drivers/pci/msi.c (ffffffff81654f71)
Location: drivers/pci/msi.c:136
Inline: True
Inline callers:
  - drivers/pci/msi.c:default_restore_msi_irqs
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
In drivers/pci/msi.c (ffffffff8165ea61)
Location: drivers/pci/msi.c:139
Inline: True
Inline callers:
  - drivers/pci/msi.c:default_restore_msi_irqs
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
In drivers/pci/msi.c (ffffffff81640f51)
Location: drivers/pci/msi.c:109
Inline: True
Inline callers:
  - drivers/pci/msi.c:default_restore_msi_irqs
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
In drivers/pci/msi.c (ffffffff816b1ba1)
Location: drivers/pci/msi.c:109
Inline: True
Inline callers:
  - drivers/pci/msi.c:default_restore_msi_irqs
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010715838)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffff800010715838-ffff8000107158c8: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c08a01e8)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
c08a01e8-c08a027c: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c000000000885800)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
c000000000885800-c0000000008858d0: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004defc2)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffe0004defc2-ffffffe0004df036: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f5d0)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8159f5d0-ffffffff8159f63e: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158e760)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8158e760-ffffffff8158e7ce: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159fb50)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8159fb50-ffffffff8159fbbe: default_restore_msi_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void default_restore_msi_irq(struct pci_dev *dev, int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b9f80)
Location: drivers/pci/msi.c:136
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff815b9f80-ffffffff815b9fee: default_restore_msi_irq (STB_LOCAL)
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
