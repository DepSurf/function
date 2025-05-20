# Function: <code>msi_capability_init</code>

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
In drivers/pci/msi.c (ffffffff81454810)
Location: drivers/pci/msi.c:608
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff814a12eb)
Location: drivers/pci/msi.c:612
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff814c2eb5)
Location: drivers/pci/msi.c:621
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff814cd3d1)
Location: drivers/pci/msi.c:600
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff8150d911)
Location: drivers/pci/msi.c:600
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff81542833)
Location: drivers/pci/msi.c:600
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff81559bf8)
Location: drivers/pci/msi.c:599
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff81589ca5)
Location: drivers/pci/msi.c:622
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff815ab0d5)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int msi_capability_init(struct pci_dev *dev, int nvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:623
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81653d80-ffffffff81653ff6: msi_capability_init (STB_LOCAL)
ffffffff8165539a-ffffffff816553f3: msi_capability_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int msi_capability_init(struct pci_dev *dev, int nvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:647
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8165e1e0-ffffffff8165e448: msi_capability_init (STB_LOCAL)
ffffffff81bf8ec1-ffffffff81bf8f18: msi_capability_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int msi_capability_init(struct pci_dev *dev, int nvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:638
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81640560-ffffffff81640868: msi_capability_init (STB_LOCAL)
ffffffff81bead1b-ffffffff81bead4c: msi_capability_init.cold (STB_LOCAL)
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
In drivers/pci/msi.c (ffffffff816b0bf2)
Location: drivers/pci/msi.c:537
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d4198)
Location: drivers/pci/msi/msi.c:430
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msi_capability_init(struct pci_dev *dev, int nvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f4ee0)
Location: drivers/pci/msi/msi.c:347
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff818f4ee0-ffffffff818f514f: msi_capability_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msi_capability_init(struct pci_dev *dev, int nvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81938310)
Location: drivers/pci/msi/msi.c:347
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81938310-ffffffff8193857f: msi_capability_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msi_capability_init(struct pci_dev *dev, int nvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81981170)
Location: drivers/pci/msi/msi.c:348
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81981170-ffffffff819813df: msi_capability_init (STB_LOCAL)
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
In drivers/pci/msi.c (ffff800010714868)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (c089f0f4)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (c0000000008841c4)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffe0004de22e)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff8159e8a5)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff8158da35)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff8159ee25)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
In drivers/pci/msi.c (ffffffff815b9255)
Location: drivers/pci/msi.c:623
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
