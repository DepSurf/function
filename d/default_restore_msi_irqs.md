# Function: <code>default_restore_msi_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81454d40)
Location: drivers/pci/msi.c:272
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff81454d40-ffffffff81454d7e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a199e)
Location: drivers/pci/msi.c:278
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff814a1950-ffffffff814a198e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c35ee)
Location: drivers/pci/msi.c:278
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff814c35a0-ffffffff814c35de: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cdc7e)
Location: drivers/pci/msi.c:259
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff814cdc30-ffffffff814cdc6e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150e1be)
Location: drivers/pci/msi.c:259
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8150e170-ffffffff8150e1ae: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81543095)
Location: drivers/pci/msi.c:259
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff81543050-ffffffff8154308e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8155a435)
Location: drivers/pci/msi.c:259
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8155a3f0-ffffffff8155a42e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158a535)
Location: drivers/pci/msi.c:267
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8158a4f0-ffffffff8158a52e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815abeb5)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff815abe70-ffffffff815abeae: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81654f40)
Location: drivers/pci/msi.c:268
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff81654f40-ffffffff81654fca: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165ea30)
Location: drivers/pci/msi.c:271
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8165ea30-ffffffff8165eaba: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640f20)
Location: drivers/pci/msi.c:242
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff81640f20-ffffffff81640faa: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b1b70)
Location: drivers/pci/msi.c:245
Inline: False
Direct callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff816b1b70-ffffffff816b1bfa: default_restore_msi_irqs (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff80001071593c)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffff8000107158c8-ffff800010715920: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c08a02d4)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
c08a027c-c08a02c0: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c00000000088596c)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
c0000000008858d0-c000000000885944: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004df096)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffe0004df036-ffffffe0004df07c: default_restore_msi_irqs (STB_GLOBAL)
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
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159f685)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8159f640-ffffffff8159f67e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158e815)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8158e7d0-ffffffff8158e80e: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159fc05)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8159fbc0-ffffffff8159fbfe: default_restore_msi_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void default_restore_msi_irqs(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815ba035)
Location: drivers/pci/msi.c:268
Inline: True
Inline callers:
  - drivers/pci/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff815b9ff0-ffffffff815ba02e: default_restore_msi_irqs (STB_GLOBAL)
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
