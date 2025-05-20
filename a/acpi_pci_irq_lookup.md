# Function: <code>acpi_pci_irq_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81487254)
Location: drivers/acpi/pci_irq.c:313
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
```
**Symbols:**

```
ffffffff81487254-ffffffff814873b0: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff814d5ea4)
Location: drivers/acpi/pci_irq.c:311
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff814d5ea4-ffffffff814d6000: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff814f84fc)
Location: drivers/acpi/pci_irq.c:311
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff814f84fc-ffffffff814f8658: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81507260)
Location: drivers/acpi/pci_irq.c:311
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81507260-ffffffff81507410: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81549530)
Location: drivers/acpi/pci_irq.c:311
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81549530-ffffffff8154981f: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8157f660)
Location: drivers/acpi/pci_irq.c:311
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff8157f660-ffffffff8157f938: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff81597380)
Location: drivers/acpi/pci_irq.c:311
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81597380-ffffffff81597658: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815c8530-ffffffff815c87ae: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff815c8b2f-ffffffff815c8b81: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815e9750-ffffffff815e99ce: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff815e9d4f-ffffffff815e9da1: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff816951c0-ffffffff816953de: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff81695791-ffffffff816957b2: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff816b2410-ffffffff816b262e: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff81c02114-ffffffff81c02135: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:291
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81694700-ffffffff816948f8: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff81bf390f-ffffffff81bf3967: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:291
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff8170a410-ffffffff8170a5ff: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff81cf0564-ffffffff81cf05bc: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:291
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff81838890-ffffffff81838a93: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff81eb83e9-ffffffff81eb8441: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff8196dc30)
Location: drivers/acpi/pci_irq.c:291
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff8196dc30-ffffffff8196de8b: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819b4160)
Location: drivers/acpi/pci_irq.c:291
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff819b4160-ffffffff819b43b2: acpi_pci_irq_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffffffff819fe760)
Location: drivers/acpi/pci_irq.c:291
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff819fe760-ffffffff819fe9b2: acpi_pci_irq_lookup (STB_LOCAL)
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
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/pci_irq.c (ffff800010776870)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffff800010776870-ffff800010776990: acpi_pci_irq_lookup (STB_LOCAL)
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
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815da720-ffffffff815da861: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff815dab7f-ffffffff815dabdc: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815c4340-ffffffff815c4481: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff815c479f-ffffffff815c47fc: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815dda30-ffffffff815ddcae: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff815de02f-ffffffff815de081: acpi_pci_irq_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct acpi_prt_entry *acpi_pci_irq_lookup(struct pci_dev *dev, int pin);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/pci_irq.c (0)
Location: drivers/acpi/pci_irq.c:298
Inline: False
Direct callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_disable
  - drivers/acpi/pci_irq.c:acpi_pci_irq_enable
```
**Symbols:**

```
ffffffff815f78f0-ffffffff815f7b6e: acpi_pci_irq_lookup (STB_LOCAL)
ffffffff815f7eef-ffffffff815f7f41: acpi_pci_irq_lookup.cold (STB_LOCAL)
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
