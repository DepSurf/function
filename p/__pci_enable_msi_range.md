# Function: <code>__pci_enable_msi_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a1260)
Location: drivers/pci/msi.c:1042
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors
  - drivers/pci/msi.c:pci_enable_msi_range
```
**Symbols:**

```
ffffffff814a1260-ffffffff814a1579: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c2e30)
Location: drivers/pci/msi.c:1062
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi_range
```
**Symbols:**

```
ffffffff814c2e30-ffffffff814c30fd: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cd350)
Location: drivers/pci/msi.c:1022
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff814cd350-ffffffff814cd5ef: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150d890)
Location: drivers/pci/msi.c:1022
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff8150d890-ffffffff8150db2f: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81542780)
Location: drivers/pci/msi.c:1022
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff81542780-ffffffff81542a1f: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, const struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81559b30)
Location: drivers/pci/msi.c:1020
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff81559b30-ffffffff81559dea: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1055
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff81589c00-ffffffff81589e82: __pci_enable_msi_range (STB_LOCAL)
ffffffff8158a980-ffffffff8158a99e: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff815ab030-ffffffff815ab2b2: __pci_enable_msi_range (STB_LOCAL)
ffffffff815ac2b9-ffffffff815ac2d7: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff81654000-ffffffff8165419b: __pci_enable_msi_range (STB_LOCAL)
ffffffff816553f3-ffffffff81655412: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1080
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff8165e450-ffffffff8165e5eb: __pci_enable_msi_range (STB_LOCAL)
ffffffff81bf8f18-ffffffff81bf8f37: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1086
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff81640870-ffffffff81640a09: __pci_enable_msi_range (STB_LOCAL)
ffffffff81bead4c-ffffffff81bead6b: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:994
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff816b0ac0-ffffffff816b0e6f: __pci_enable_msi_range (STB_LOCAL)
ffffffff81ce5b50-ffffffff81ce5b8a: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (0)
Location: drivers/pci/msi/msi.c:857
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff817d4000-ffffffff817d4388: __pci_enable_msi_range (STB_LOCAL)
ffffffff81eac63b-ffffffff81eac653: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f54b0)
Location: drivers/pci/msi/msi.c:405
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/api.c:pci_enable_msi
```
**Symbols:**

```
ffffffff818f54b0-ffffffff818f56d6: __pci_enable_msi_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff819388e0)
Location: drivers/pci/msi/msi.c:405
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/api.c:pci_enable_msi
```
**Symbols:**

```
ffffffff819388e0-ffffffff81938b0d: __pci_enable_msi_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81981740)
Location: drivers/pci/msi/msi.c:406
Inline: False
Direct callers:
  - drivers/pci/msi/api.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi/api.c:pci_enable_msi
```
**Symbols:**

```
ffffffff81981740-ffffffff8198196d: __pci_enable_msi_range (STB_GLOBAL)
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
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff8000107147b8)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffff8000107147b8-ffff800010714a48: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089f040)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
c089f040-c089f430: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c0000000008840c0)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
c0000000008840c0-c00000000088446c: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004de1b8)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffe0004de1b8-ffffffe0004de3f2: __pci_enable_msi_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff8159e800-ffffffff8159ea82: __pci_enable_msi_range (STB_LOCAL)
ffffffff8159fa89-ffffffff8159faa7: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff8158d990-ffffffff8158dc12: __pci_enable_msi_range (STB_LOCAL)
ffffffff8158ec19-ffffffff8158ec37: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff8159ed80-ffffffff8159f002: __pci_enable_msi_range (STB_LOCAL)
ffffffff815a0009-ffffffff815a0027: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __pci_enable_msi_range(struct pci_dev *dev, int minvec, int maxvec, struct irq_affinity *affd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:1056
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_alloc_irq_vectors_affinity
  - drivers/pci/msi.c:pci_enable_msi
```
**Symbols:**

```
ffffffff815b91b0-ffffffff815b9432: __pci_enable_msi_range (STB_LOCAL)
ffffffff815ba439-ffffffff815ba457: __pci_enable_msi_range.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct irq_affinity *affd</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct irq_affinity *affd</code> ➡️ <code>struct irq_affinity *affd</code>
</li>
</ul>
</details>
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
