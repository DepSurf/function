# Function: <code>acpi_pci_irq_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff814873b0)
Location: drivers/acpi/pci_irq.c:393
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff814873b0-ffffffff81487591: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff814d6000)
Location: drivers/acpi/pci_irq.c:408
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff814d6000-ffffffff814d6216: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff814f8658)
Location: drivers/acpi/pci_irq.c:408
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff814f8658-ffffffff814f8876: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81507410)
Location: drivers/acpi/pci_irq.c:408
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff81507410-ffffffff8150764d: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81549820)
Location: drivers/acpi/pci_irq.c:408
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff81549820-ffffffff81549abf: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8157f940)
Location: drivers/acpi/pci_irq.c:408
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff8157f940-ffffffff8157fbe3: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81597660)
Location: drivers/acpi/pci_irq.c:408
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff81597660-ffffffff81597973: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff815c8b81-ffffffff815c8c13: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff815c87b0-ffffffff815c8a3d: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff815e9da1-ffffffff815e9e3b: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff815e99d0-ffffffff815e9c5d: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff816957b2-ffffffff8169584a: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff816953e0-ffffffff81695662: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff81c02135-ffffffff81c021cd: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff816b2630-ffffffff816b28b2: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:383
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff81bf3967-ffffffff81bf39ff: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff81694900-ffffffff81694b46: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:383
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff81cf05bc-ffffffff81cf0654: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff8170a600-ffffffff8170a840: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:383
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff81eb8441-ffffffff81eb84d5: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff81838aa0-ffffffff81838d03: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8196dea0)
Location: drivers/acpi/pci_irq.c:383
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff8196dea0-ffffffff8196e19c: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819b43d0)
Location: drivers/acpi/pci_irq.c:383
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff819b43d0-ffffffff819b46d4: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819fe9d0)
Location: drivers/acpi/pci_irq.c:383
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff819fe9d0-ffffffff819fecd4: acpi_pci_irq_enable (STB_GLOBAL)
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
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffff800010776990)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/arm64/kernel/pci.c:pcibios_alloc_irq
```
**Symbols:**

```
ffff800010776990-ffff800010776bb8: acpi_pci_irq_enable (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff815dabdc-ffffffff815dac76: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff815da870-ffffffff815daa87: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff815c47fc-ffffffff815c4896: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff815c4490-ffffffff815c46a7: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff815de081-ffffffff815de11b: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff815ddcb0-ffffffff815ddf3d: acpi_pci_irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_pci_irq_enable(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:395
Inline: False
Direct callers:
  - arch/x86/pci/acpi.c:pci_acpi_init
```
**Symbols:**

```
ffffffff815f7f41-ffffffff815f7fdb: acpi_pci_irq_enable.cold (STB_LOCAL)
ffffffff815f7b70-ffffffff815f7dfd: acpi_pci_irq_enable (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
